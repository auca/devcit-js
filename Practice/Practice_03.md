# DEVCIT-JS
Практическая работа №3
======================

## Организация работ

Рекомендуется выделить отдельную директорию для всех практических работ и задач.

### Пример организации директории

```
F:\
|
|--DEVCIT-JS
|----Practice_01_Task_01
|----Practice_01_Task_02
|----...
|----Practice_02_Task_01
|----...
|----URI_Task_1001
|----URI_Task_1002
|----...
```

## Ключевые инструменты разработчика

* [Google Chrome](https://www.google.com/chrome)
* [Visual Studio Code](https://code.visualstudio.com)
* [Node.js](https://nodejs.org/en)

### Альтернативная среда разработки (по желанию)

* [IntelliJ WebStorm](https://www.jetbrains.com/webstorm)

## Задача № 1: Введение в HTML

Создайте HTML страницу `markdown-help.html` с информацией о языке [Markdown](https://daringfireball.net/projects/markdown/).

Используйте следующие HTML-элементы для структурирования информации о синтаксисе Markdown.

* Заголовки и подзаголовки
* Пункты
* Разрывы строк и горизонтальные линии
* Полужирный и курсивный текст
* Ссылки
* Упорядоченные и неупорядоченные списки
* [Списки определений](http://kramdown.gettalong.org/syntax.html#definition-lists)
* Длинные цитаты
* Предварительно отформатированный текст и код
* [Изображения](https://github.com/dcurtis/markdown-mark)
* [Таблицы](http://kramdown.gettalong.org/syntax.html#tables)

### Дополнительные требования

* Укажите правильный тип документа HTML5.
* Не забудьте указать язык документа.
* Предоставьте метаинформацию о кодировке, авторе документа.
* Укажите название документа.
* Используйте комментарий HTML хотя бы один раз.
* Используйте любую HTML-сущность хотя бы один раз.
* Сгруппируйте логические части вашего документа (навигация, статья, заголовок, разделы, нижний колонтитул…)

## Documentation

* [HTML](https://developer.mozilla.org/ru/docs/Glossary/HTML)
* [Doctype](https://developer.mozilla.org/ru/docs/Glossary/Doctype)

## Tags

* [html](https://developer.mozilla.org/ru/docs/Web/HTML/Element/html)
* [head](https://developer.mozilla.org/ru/docs/Web/HTML/Element/head)
* [meta](https://developer.mozilla.org/ru/docs/Web/HTML/Element/meta)
* [title](https://developer.mozilla.org/ru/docs/Web/HTML/Element/title)
* [body](https://developer.mozilla.org/ru/docs/Web/HTML/Element/body)
* [h\[1-6\]](https://developer.mozilla.org/ru/docs/Web/HTML/Element/Heading_Elements)
* [p](https://developer.mozilla.org/ru/docs/Web/HTML/Element/p)
* [br](https://developer.mozilla.org/ru/docs/Web/HTML/Element/br)
* [hr](https://developer.mozilla.org/ru/docs/Web/HTML/Element/hr)
* [strong](https://developer.mozilla.org/ru/docs/Web/HTML/Element/strong)
* [em](https://developer.mozilla.org/ru/docs/Web/HTML/Element/em)
* [a](https://developer.mozilla.org/ru/docs/Web/HTML/Element/a)
* [ol](https://developer.mozilla.org/ru/docs/Web/HTML/Element/ol)
* [ul](https://developer.mozilla.org/ru/docs/Web/HTML/Element/ul)
* [li](https://developer.mozilla.org/ru/docs/Web/HTML/Element/li)
* [dl](https://developer.mozilla.org/ru/docs/Web/HTML/Element/dl)
* [dt](https://developer.mozilla.org/ru/docs/Web/HTML/Element/dt)
* [dd](https://developer.mozilla.org/ru/docs/Web/HTML/Element/dd)
* [blockquote](https://developer.mozilla.org/ru/docs/Web/HTML/Element/blockquote)
* [pre](https://developer.mozilla.org/ru/docs/Web/HTML/Element/pre)
* [code](https://developer.mozilla.org/ru/docs/Web/HTML/Element/code)
* [img](https://developer.mozilla.org/ru/docs/Web/HTML/Element/img)
* [table](https://developer.mozilla.org/ru/docs/Web/HTML/Element/table)
* [tr](https://developer.mozilla.org/ru/docs/Web/HTML/Element/tr)
* [th](https://developer.mozilla.org/ru/docs/Web/HTML/Element/th)
* [td](https://developer.mozilla.org/ru/docs/Web/HTML/Element/td)
* [div](https://developer.mozilla.org/ru/docs/Web/HTML/Element/div)
* [span](https://developer.mozilla.org/ru/docs/Web/HTML/Element/span)
* [main](https://developer.mozilla.org/ru/docs/Web/HTML/Element/main)
* [nav](https://developer.mozilla.org/ru/docs/Web/HTML/Element/nav)
* [section](https://developer.mozilla.org/ru/docs/Web/HTML/Element/section)
* [article](https://developer.mozilla.org/ru/docs/Web/HTML/Element/article)
* [header](https://developer.mozilla.org/ru/docs/Web/HTML/Element/header)
* [footer](https://developer.mozilla.org/ru/docs/Web/HTML/Element/footer)

## Задача № 2: Загрузка на сервер

Используйте программу командной строки `scp` или `rsync` для загрузни документа в вашу домашнюю директорию сервера `auca.space`.

Попробуйте сделать тоже самое, но при помощи программы [WinSCP]( https://winscp.net/eng/downloads.php).

## Задача № 3: Запуск сервера

Запустите сервер для предоставления доступа к вашей странице. Для подключения к серверу используйте протокол
`ssh`. Используйте порт в формате `80XX`, где XX нужно заменить на ваш ID в системе.

```bash
python -m SimpleHTTPServer <80XX>
```

Зайдите на вашу страницу через браузер по адресу `http://auca.space:80XX`.

Сервер можно остановить командой `CTRL+C`. Для завершения удаленной сессии `ssh`, используйте команду `exit`.

## Задание на дом

### URI

Задания с 1001 по 1020 <https://www.urionlinejudge.com.br/judge/en/problems/index/1>

Перевод заданий можно найти по ссылке <https://github.com/auca/devcit-js/blob/master/Practice/URI_Translations.md>
