## Здравствуйте! Здесь вы можете посмотреть примеры моих личных проектов за 2018-2022 годы.
Они упорядочены по годам, сначала идут самые новые. Мои проекты 2022-2024 года я не хочу выкладывать в открытый доступ, но могу показать при встрече.

### 1. Менеджер памяти со свопом.
[C++17, Cmake, bash], ноябрь 2022 

В качестве теста я реализовал многопоточное копирование файлов, размер которых до 100 раз больше размера оперативной памяти. 
[Это было тестовое задание, но в итоге получился небольшой проект](https://github.com/zazicam/memory_manager_with_swap)

### 2. Командная оболочка для Linux на языке Си.
[C, linux, Make], 2021.

Интересное задание из курса cs5600 ("Компьютерные системы / Операционные системы"). Надо написать свой аналог bash. В задании дается схема реализации и 70 тестов для проверки корректности выполнения. Задача - написать все недостающие функции так, чтобы прошли все тесты. [Подробное описание задания и мое решение по ссылке](https://github.com/zazicam/simple-shell)

### 3. Библиотека libbox для создания консольных игр.
[C++, WinApi, Visual Studio], 2020.

Я написал эту библиотеку для работы со школьниками. Она нужна для создания консольных игр с подвижной цветной псевдографикой. Поддерживает работу с цветным текстовым дисплеем, клавиатурой, таймером и генератором псевдослучайных чисел. Конечно, это всё обёртки над WinApi и объектами стандартной библиотеки, но они проще и интереснее для начинающих. [Примеры использования библиотеки и ее исходный код  выложен тут](https://github.com/zazicam/libbox).

### 4. Кластеризация точек на плоскости и визуализация результата.
[C++, Cmake, dlib, libpng], 2019. 

[Домашнее задание по курсу "С++ Developer. Professional" от компании OTUS](https://github.com/zazicam/otus-cpp-hw15).

### 5. Скрипт рекурсивного обхода сайта c занесением информации в базу данных.
[Python, MySQL], 2018.

Это стартовый код одного из моих проектов по мониторингу сайтов. Данный скрипт получает в качестве аргументов командной строки url сайта и выполняет обход всех его страниц до заданного уровня вложенности. Информация о структуре и содержимом сайта сохраняется в отдельную БД в таблицу pages. В процессе обхода сайта информация о найденных и обработанных страницах отображается в таблице log. [Подробное описание и исходный код скрипта выложены здесь](https://github.com/zazicam/webot)
