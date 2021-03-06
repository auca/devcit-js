# DEVCIT-JS
Практическая работа №2
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
|----Practice_01_HomeTask_01
|----Practice_01_HomeTask_02
|----...
|----Practice_02_Task_01
|----Practice_02_Task_02
|----...
|----URI_Task_1001
|----URI_Task_1002
|----...
```

## Ключевые инструменты разработчика

* [Google Chrome](https://www.google.com/chrome)
* [Visual Studio Code](https://code.visualstudio.com)

### Альтернативная среда разработки (по желанию)

* [IntelliJ WebStorm](https://www.jetbrains.com/webstorm)

## Задание №1: Перестановка

Определите две переменные в вашей программе. Считайте значения этих переменных
у пользователя при помощи функции `prompt(...)`. Напечатайте значение двух
переменных на экран до перестановки. Проведите перестановку значений в памяти и
выведите новые значения переменных на экран.

### Пример вывода

```
Первое значение: 2
Второе значение: 3
До перестановки: a = 2; b = 3;
После перестановки: a = 3; b = 2;
```

## Задание №2: Перестановка без временных переменных

Напишите программу перестановки из задания №1 без использования временных
переменных.

### Пример вывода

```
Первое значение: 2
Второе значение: 3
До перестановки без доп. переменной: a = 2; b = 3;
После перестановки без доп. переменной: a = 3; b = 2;
```

## Задание №3: Сумма цифр

Сделайте запрос четырёхзначного числа у пользователя, найдите сумму всех 4-х
цифр и выведите ответ на экран

### Пример ввода и вывода

```
Введите четырёхзначное число: 1237
Сумма всех цифр числа 1237 равна 13
```

## Задание №4: Перевод единиц длины 1

Напишите программу перевода единиц длины из дюймов в сантиметры. Программа
спрашивает значение в дюймах и вычисляет значение в сантиметрах, исходя из
следующего соотношения: 1 дюйм = 2.54 сантиметров.

### Форма ввода и вывода

```
Введите значение в дюймах: 17
17.00 дюйм. = 43.18 см.
```

## Задание №5: Перевод температурных значений

Напишите программу перевода единиц температуры. Программа спрашивает значение в
градусах Фаренгейта и вычисляет значение в градусах Цельсия.

Ниже приведена формула расчёта

[°C] = 5⁄9 × ([°F] − 32) 

### Пример вывода

```
Введите температуру в градусах Фаренгейта: 114
Температура в градусах Цельсия: 45.56
```

## Задание №6: Генератор случайных чисел

Создайте программу генерации случайных чисел. Пользователь должен указать
минимальное и максимальное значение величин в программе.

### Пример вывода

```
Введите минимальное значение: 10
Введите максимальное значение: 100
Случайно число от 10 до 100: 42
```

* [Math.random](https://developer.mozilla.org/ru/docs/Web/JavaScript/Reference/Global_Objects/Math/random)

## Домашнее задание №1: Перевод единиц длины 2

Напишите программу перевода единиц длины из футов в метры. Программа
спрашивает значение в футах и вычисляет значение в метрах, исходя из
следующего соотношения: 1 фут = 0.305 метров.

Выведите результат в параграф текста HTML страницы.

### Пример ввода и вывода

```
Введите значение в футах: 23
17.00 ф. = 7.02 м.
```

## Домашнее задание №2: Цилиндр

Напишите программу, которая считывает радиус и длинну цилиндра, и рассчитывает
площадь и объем используя следующие формулы

```
площадь = радиус * радиус * Pi
объем = площадь * длинна
```

Выведите результат в параграф текста HTML страницы.

### Пример вывода

```
Введите радиус и длину цилиндра: 5.5 12
Площадь равна 95.03
Объем равен 1140.40
```

## Домашнее задание №3: BMI

Индекс массы тела (Body Mass Index, BMI) является показателем здоровья по весу.
Он может быть рассчитан путем взятия веса в килограммах и деления на квадрат
вашего роста в метрах. Напишите программу, которая спршивает пользователя вес в
фунтах и высоту в дюймах и отображает BMI. Обратите внимание, что один фунт
равен 0.45359237 килограммам, а один дюйм — 0.0254 метра.

Выведите результат в параграф текста HTML страницы.

### Пример вывода

```
Введите вес в фунтах: 95.5
Введите высоту в дюймах: 50
BMI равен 26.86
```

## Домашнее задание №4: Рост населения 1

Государство США определяет рост населения исходя из следующих стат-наблюдений.
  
* Каждые 7 секунд в стране рождается 1 человек.
* Каждые 13 секунд в стране умирает 1 человек.
* Каждые 45 секунд в страну въезжает новый иммигрант.

Вычислите рост населения, если предположить, что темп роста не изменится...
    
* через 1 год
* через 10 лет
* через 100 лет
* через 1000 лет

Нынешнее население: 312 032 486 человек
Дней в году: 365 (для упрощения расчета)

Выведите результат в параграф текста HTML страницы.

### Пример вывода

```
Население США через 1 год: ...
Население США через 10 лет: ...
Население США через 100 лет: ...
Население США через 1000 лет: ...
```

## Домашнее задание №5: Рост населения 2

Измените код пред. упражнения, чтобы предложить пользователю ввести количество
лет. Отобразить население после указанного количества лет.

### Пример вывода

```
Введите количество лет: 5
Население через 5 лет 325932970
```

##  Сдача работ

Получите аккаунт в системе Canvas. Заведите новый аккаунт в системе GitHub и
получите от преподавателя ссылку на создание частного репозитория для хранения
работ этого курса. Загружайте решения в репозиторий посредством системы Git.
Когда все работы практического задания 2 будут загружены, скопируйте ID
последнего коммита и отошлите в систему Canvas до финального срока сдачи.

### URI

Задания с 1001 по 1010 <https://www.urionlinejudge.com.br/judge/en/problems/index/1>

Перевод заданий можно найти по ссылке <https://github.com/auca/devcit-js/blob/master/Practice/URI_Translations_Part_1.md>

