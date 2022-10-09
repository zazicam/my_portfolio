## Мое портфолио
Я разместил здесь примеры моего кода вместе с кратким описанием. Это мои личные проекты или решения задач с курсов, которые я проходил за последние 3 года. 

### 1. Кластеризация точек на плоскости и визуализация результата 
[C++, Cmake, dlib, libpng], 2019. 

Это одно из домашних заданий по курсу "С++ Developer. Professional" от компании OTUS. Я его проходил в 2019 году и считаю, что этот [код можно показать](https://github.com/zazicam/otus-cpp-hw15).

### 2. Шаблонный класс 2-мерной разреженой бесконечной матрицы 
[С++, Cmake, GTest], 2019.

Также задание по курсу "С++ Developer. Professional" 2019 года. [Пример моего кода с использованием шаблонов С++](https://github.com/zazicam/otus-cpp-hw6).

### 3. Командная оболочка для Linux на языке Си
[C, linux, Make], 2021.

Это довольно интересное задание из курса cs5600 ("Компьютерные системы / Операционные системы"). По сути надо написать свой аналог bash или zsh. В задании дается "скелет" командной оболочки с большим количеством комментариев по реализации и прилагаются 70 тестов для проверки корректности выполнения. Задача - написать все недостающие функции так, чтобы прошли все тесты. [Подробное описание задания и мое решение по ссылке](https://github.com/zazicam/simple-shell)

### 4. Библиотека libbox для создания консольных игр (для обучения основам С++)
[C++, WinApi, Visual Studio], 2020.

Я достаточно много преподавал С++ школьниками и студентам. При этом одной из проблем освоения языка С++ является отсутствие простых и удобных библиотек для начинающих (если сравнивать, например, с языком Python). Как преподавателю мне тоже не хватало такой библиотеки, поэтому я написал ее сам. Она позволяет быстрее и проще создавать консольные программы с подвижной цветной псевдографикой. Поддерживает работу с цветным текстовым дисплеем, клавиатурой, таймером и генератором псевдослучайных чисел. Конечно, это все просто обертки над WinApi и объектами стандартной библиотеки, но они удобнее и проще для начинающих. [Примеры использования библиотеки и ее исходный код  выложен тут](https://github.com/zazicam/libbox).

### 5. Группа вк "Hello С++" c обучающим ботом для школьников.
[Python, bash, vkapi], 2020.

Это еще один мой проект, связанный с преподаванием программирования. Для своей группы вк, посвященной языку С++ для школьников я написал обучаеющего бота "Машу". Бот Маша умеет проверять решения домашних заданий (компилирует код, прогоняет через тесты, отправляет отчет и сохраняет результат), проводить квизы по С++, выдавать программистские шуточки и мемы. Код бота я не выложу пока, но вы можете его потестировать сами. [Подробное описание тут](https://github.com/zazicam/my_portfolio/blob/main/texts/vkbot.md).

### 6. Скрипт рекурсивного обхода сайта c занесением информации в базу данных
[Python, MySQL], 2018.

Это стартовый код одного из моих экспериментальных проектов по мониторингу сайтов. Данный скрипт получает в качестве аргументов командной строки url сайта и выполняет обход всех его страниц до заданного уровня вложенности. Информация о структуре и содержимом сайта сохраняется в отдельную БД в таблицу pages. В процессе обхода сайта информация о найденных и обработанных страницах отображается в таблице log. [Подробное описание и исходный код скрипта выложены здесь](https://github.com/zazicam/webot)
