# DEVCIT-JS
Практическая работа №4
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
* [Git, SSH, SCP](https://git-scm.com/)
* [WinSCP](https://winscp.net/eng/downloads.php)

### Альтернативная среда разработки (по желанию)

* [IntelliJ WebStorm](https://www.jetbrains.com/webstorm)

## Задача № 1: Введение в CSS

Используйте `markdown-help.html` из предыдущего задания и создайте как минимум два
разных стиля для вашей страницы используя язык [CSS](https://developer.mozilla.org/ru/docs/Web/CSS).

Каждый стиль страницы должен быть представлен как отдельный файл `.css` и связан
тегом `<link rel="stylesheet" href="file_name.css">` (не забудьте заменить
`file_name` именем вашего файла стилей).

В своей работе вам нужно хотя бы раз использовать следующее

### CSS селекторы

<https://www.w3.org/TR/selectors>

* _E_: элемент типа E
* _.warning_: элемент с классом "warning"
* _E.warning_: элемент E с классом "warning"
* _#myid_: элемент с ID "myid"
* _E#myid_: элемент E с ID "myid"
* _E F_: все дочерние элементы F элемента E
* _E > F_: первый прямой наследник F от элемента E
* _E:active_ и _E:hover_ и _E:focus_: элемент E при определенных действий пользователя (нажатие, наведение курсора, выделение через Tab)
* _E[foo]_: элемент E с атрибутом "foo"
* _E[foo="bar"]_: элемент E с атрибутом "foo" со значением "bar"
* _selector_, _selector_, ...: группа селекторов

### CSS свойства

<https://developer.mozilla.org/ru/docs/Web/CSS/Reference>

* color
* background (background, background-color, background-image...)
* margin (margin, margin-top|bottom|left...)
* padding (padding, padding-top|bottom|left...)
* border (border, border-style, border-color, border-width...)
* font (font, font-family, font-size, font-style, font-weight...)
* width, height...
* display (inline, block)
* list-style

## Документация

* [CSS](https://developer.mozilla.org/ru/docs/Web/CSS)
* [CSS, Syntax and Form](https://developer.mozilla.org/ru/docs/Web/CSS/Syntax)
* [CSS, Selectors](https://developer.mozilla.org/ru/docs/Web/Guide/CSS/Getting_started/Selectors)
* [CSS, Inheritance](https://developer.mozilla.org/ru/docs/Web/CSS/inheritance)
* [CSS, Specificity](https://developer.mozilla.org/ru/docs/Web/CSS/Specificity)
* [CSS, Box Model](https://developer.mozilla.org/ru/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
* [CSS, Shorthand Properties](https://developer.mozilla.org/ru/docs/Web/CSS/Shorthand_properties)
* [CSS, Colors](https://developer.mozilla.org/ru/docs/Web/CSS/color_value)
* [CSS, Length](https://developer.mozilla.org/ru/docs/Web/CSS/length)
* [CSS, Percentage](https://developer.mozilla.org/ru/docs/Web/CSS/percentage)
* [CSS, Font Face](https://developer.mozilla.org/ru/docs/Web/CSS/@font-face)

## Другие ресурсы

* [CSS3 Patterns](http://lea.verou.me/css3patterns)

## Задача № 2: Загрузка на сервер

Используйте программу командной строки `scp` или `rsync` для загрузни документа в вашу домашнюю директорию сервера `auca.space`.

Попробуйте сделать тоже самое, но при помощи программы [WinSCP]( https://winscp.net/eng/downloads.php).

## Задача № 3: Запуск сервера

Запустите веб-сервер для предоставления доступа к вашей странице. Используйте порт в формате `80XX` для вашего сервера, где XX нужно заменить на ваш ID в системе. Для подключения к системе `auca.space` для администрирования используйте протокол `ssh`.

```bash
python -m SimpleHTTPServer <80XX>
```

Зайдите на вашу страницу через браузер по адресу `http://auca.space:80XX`.

Сервер можно остановить командой `CTRL+C`. Для завершения удаленной сессии `ssh`, используйте команду `exit`.

## Задание на дом

Создайте страницу-визитку для некоторой компании на ваш выбор. Используйте все HTML элементы и свойства CSS
из работ 3 и 4. Загрузите страницу на сервер `auca.space` по завершению работы.
