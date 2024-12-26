<h1>Лабораторна робота 1: Вивчення Git</h1>

Налаштування глобальних параметрів Git для користувача. Встановлення імені користувача, електронної пошти, гілки за замовчуванням та параметрів обробки закінчень рядків.

<p align="center">
<img src="Screenshots/ (1).png" alt="(1)"/>
</p>

Створення робочого середовища проекту. Команди mkdir work створює нову директорію, cd work переходить до неї, а touch hello.html створює HTML файл.

<p align="center">
<img src="Screenshots/ (2).png" alt="(2)"/>
</p>

Редагування файлу hello.html з додаванням базового тексту "Hello, World".

<p align="center">
<img src="Screenshots/ (3).png" alt="(3)"/>
</p>

Ініціалізація Git репозиторію та створення першого коміту. Команди git init створює новий репозиторій, git add додає файл для відстеження, а git commit зберігає зміни.

<p align="center">
<img src="Screenshots/ (4).png" alt="(4)"/>
</p>

Перевірка статусу репозиторію за допомогою команди git status. Показує, що всі зміни збережені та робоча директорія чиста.

<p align="center">
<img src="Screenshots/ (5).png" alt="(5)"/>
</p>

Створення простого HTML-файлу з тегом заголовка першого рівня, що містить текст "Hello, World!".

<p align="center">
<img src="Screenshots/ (6).png" alt="(6)"/>
</p>

Перевірка статусу репозиторію за допомогою команди git status, яка показує невідстежувані зміни у файлі hello.html.

<p align="center">
<img src="Screenshots/ (7).png" alt="(7)"/>
</p>

Додавання файлу hello.html до індексу Git за допомогою команди git add. Повторна перевірка статусу показує, що файл готовий до коміту.

<p align="center">
<img src="Screenshots/ (8).png" alt="(8)"/>
</p>

Спроба створення коміту за допомогою команди git commit, система очікує закриття файлу редактора.

<p align="center">
<img src="Screenshots/ (9).png" alt="(9)"/>
</p>

Відкриття файлу COMMIT_EDITMSG для введення повідомлення коміту. В даному випадку додано повідомлення "Added h1 tag".

<p align="center">
<img src="Screenshots/ (10).png" alt="(10)"/>

Успішне виконання коміту з повідомленням "Added h1 tag" та перевірка статусу, яка показує чистий робочий каталог без змін.

<p align="center">
<img src="Screenshots/ (11).png" alt="(11)"/>
</p>

Розширення HTML-файлу шляхом додавання базової структури документа з тегами html та body.

<p align="center">
<img src="Screenshots/ (12).png" alt="(12)"/>
</p>

Додавання змінененого файлу hello.html до індексу Git за допомогою команди git add.

<p align="center">
<img src="Screenshots/ (13).png" alt="(13)"/>
</p>

Додавання тегу head до HTML-структури документа для подальшого розширення функціональності сторінки.

<p align="center">
<img src="Screenshots/ (14).png" alt="(14)"/>
</p>

Серія команд Git для відстеження змін: перевірка статусу, додавання змін до індексу з допомогою "git add .", та створення коміту з повідомленням "Added HTML header".

<p align="center">
<img src="Screenshots/ (15).png" alt="(15)"/>
</p>

Перегляд історії комітів за допомогою команди git log, яка показує всі зміни, включаючи додавання HTML-заголовка, стандартних тегів та початковий коміт.

<p align="center">
<img src="Screenshots/ (16).png" alt="(16)"/>
</p>

Використання різних параметрів команди git log для отримання більш компактного виводу історії: обмеження кількості комітів, фільтрація за часом та автором.

<p align="center">
<img src="Screenshots/ (17).png" alt="(17)"/>
</p>

Налаштування глобального формату виводу git log для більш компактного відображення інформації про коміти.

<p align="center">
<img src="Screenshots/ (18).png" alt="(18)"/>
</p>

Демонстрація роботи з різними версіями файлу за допомогою git checkout. Перехід до початкового коміту та порівняння вмісту файлу hello.html в різних версіях.

<p align="center">
<img src="Screenshots/ (19).png" alt="(19)"/>
</p>

Створення тегів для версій проекту. Додавання тегу v1 та v1-beta для позначення важливих етапів розробки, з подальшим переглядом вмісту файлів на цих етапах.

<p align="center">
<img src="Screenshots/ (20).png" alt="(20)"/>
</p>

Перевірка вмісту репозиторію при різних тегах за допомогою команд git checkout v1 та git checkout v1-beta, що показує різні стани проекту.

<p align="center">
<img src="Screenshots/ (21).png" alt="(21)"/>
</p>

Повернення до основної гілки розробки за допомогою команди git switch main.

<p align="center">
<img src="Screenshots/ (22).png" alt="(22)"/>
</p>

Додавання небажаного коментаря до HTML-файлу, який потрібно буде видалити за допомогою git.

<p align="center">
<img src="Screenshots/ (23).png" alt="(23)"/>
</p>

Використання команди git checkout для скасування небажаних змін у файлі hello.html та повернення до попереднього стану.

<p align="center">
<img src="Screenshots/ (24).png" alt="(24)"/>
</p>

Додавання нового коментаря в секцію head HTML-документа для демонстрації роботи з індексованими змінами.

<p align="center">
<img src="Screenshots/ (25).png" alt="(25)"/>
</p>

Використання команди git add для додавання змін до індексу та git reset HEAD для скасування індексації змін у файлі hello.html.

<p align="center">
<img src="Screenshots/ (26).png" alt="(26)"/>
</p>

Додавання небажаного коментаря, який буде включено до коміту для демонстрації подальшого відкату змін.

<p align="center">
<img src="Screenshots/ (27).png" alt="(27)"/>
</p>

Створення коміту з небажаними змінами та подальше використання git revert для скасування цих змін, створюючи новий коміт, що відміняє попередні зміни.

<p align="center">
<img src="Screenshots/ (28).png" alt="(28)"/>
</p>

Створення та перегляд тегу "oops" для позначення помилкового коміту та його відкату, використання git reset --hard для повернення до конкретної версії.

<p align="center">
<img src="Screenshots/ (29).png" alt="(29)"/>
</p>

Видалення тегу "oops" за допомогою команди git tag -d та перевірка історії комітів після всіх виконаних операцій.

<p align="center">
<img src="Screenshots/ (30).png" alt="(30)"/>
</p>

Додавання коментаря з інформацією про автора у форматі HTML-коментаря на початку файлу.

<p align="center">
<img src="Screenshots/ (31).png" alt="(31)"/>
</p>

Створення нового коміту з доданим коментарем про авторські права та перегляд оновленої історії комітів.

<p align="center">
<img src="Screenshots/ (32).png" alt="(32)"/>
</p>

Оновлення інформації про автора, додавання електронної адреси до коментаря з авторськими правами.

<p align="center">
<img src="Screenshots/ (33).png" alt="(33)"/>
</p>

Фіксація змін з оновленою інформацією про автора за допомогою команди git commit та перевірка оновленої історії комітів.

<p align="center">
<img src="Screenshots/ (34).png" alt="(34)"/>
</p>

Створення нової гілки 'style' за допомогою команди git switch -c та створення файлу style.css для подальшої роботи над стилями.

<p align="center">
<img src="Screenshots/ (35).png" alt="(35)"/>
</p>

Створення файлу style.css та додавання стилів для заголовка h1, встановлюючи червоний колір тексту.

<p align="center">
<img src="Screenshots/ (36).png" alt="(36)"/>
</p>

Додавання файлу стилів до системи контролю версій за допомогою команд git add та git commit.

<p align="center">
<img src="Screenshots/ (37).png" alt="(37)"/>
</p>

Підключення створеного файлу стилів до HTML-документа за допомогою тега link у секції head.

<p align="center">
<img src="Screenshots/ (38).png" alt="(38)"/>
</p>

Фіксація змін в HTML-файлі після додавання посилання на таблицю стилів.

<p align="center">
<img src="Screenshots/ (39).png" alt="(39)"/>
</p>

Перегляд повної історії комітів та переключення між гілками main та style для порівняння версій файлів.

<p align="center">
<img src="Screenshots/ (40).png" alt="(40)"/>
</p>

Перегляд історії змін для конкретних файлів за допомогою команд git log hello.html та git log style.css, а також порівняння версій файлу hello.html за допомогою git show.

<p align="center">
<img src="Screenshots/ (41).png" alt="(41)"/>
</p>

Перейменування файлу hello.html на index.html за допомогою команди mv та перевірка статусу змін у репозиторії.

<p align="center">
<img src="Screenshots/ (42).png" alt="(42)"/>
</p>

Створення директорії css, переміщення файлу style.css до неї за допомогою git mv та фіксація змін у структурі проекту.

<p align="center">
<img src="Screenshots/ (43).png" alt="(43)"/>
</p>

Створення файлу README з коротким описом проекту для документації.

<p align="center">
<img src="Screenshots/ (44).png" alt="(44)"/>
</p>

Переключення на гілку main та додавання файлу README до репозиторію з відповідним комітом.

<p align="center">
<img src="Screenshots/ (45).png" alt="(45)"/>
</p>

Візуалізація історії комітів за допомогою команди git log --all --graph, яка показує графічне представлення гілок та їх злиття.

<p align="center">
<img src="Screenshots/ (46).png" alt="(46)"/>
</p>

Переключення на гілку style та об'єднання змін з гілки main за допомогою команди git merge, що додає файл README до гілки style.

<p align="center">
<img src="Screenshots/ (47).png" alt="(47)"/>
</p>

Повернення до гілки main для подальшої розробки.

<p align="center">
<img src="Screenshots/ (48).png" alt="(48)"/>
</p>

Додавання метаданих до HTML-документа: заголовок сторінки через тег title та текстовий параграф про вивчення Git.

<p align="center">
<img src="Screenshots/ (49).png" alt="(49)"/>
</p>

Фіксація змін метаданих та перегляд оновленої історії комітів з графічним відображенням структури гілок.

<p align="center">
<img src="Screenshots/ (50).png" alt="(50)"/>
</p>

Спроба об'єднання гілки main з гілкою style, що призвела до конфлікту в файлі index.html через різні версії файлу.

<p align="center">
<img src="Screenshots/ (51).png" alt="(51)"/>
</p>

Відображення конфліктуючих змін у файлі index.html з маркерами конфлікту та опціями для його вирішення.

<p align="center">
<img src="Screenshots/ (52).png" alt="(52)"/>
</p>

Скасування невдалої спроби злиття за допомогою команди git merge --abort та повторна спроба об'єднання гілок.

<p align="center">
<img src="Screenshots/ (53).png" alt="(53)"/>
</p>

Ручне вирішення конфлікту шляхом редагування файлу index.html та збереження правильної версії.

<p align="center">
<img src="Screenshots/ (54).png" alt="(54)"/>
</p>

Завершення процесу злиття гілок через команди git add та git commit з подальшим переглядом оновленої історії комітів.

<p align="center">
<img src="Screenshots/ (55).png" alt="(55)"/>
</p>

Перегляд графічного представлення історії комітів та виконання команди git reset --hard HEAD~2 для повернення до попереднього стану.

<p align="center">
<img src="Screenshots/ (56).png" alt="(56)"/>
</p>

Початок процесу перебазування за допомогою команди git rebase main, що призвело до конфлікту в файлі hello.html.

<p align="center">
<img src="Screenshots/ (57).png" alt="(57)"/>
</p>

Відображення конфліктуючих змін з опціями для вирішення конфлікту при перебазуванні.

<p align="center">
<img src="Screenshots/ (58).png" alt="(58)"/>
</p>

Ручне вирішення конфлікту шляхом вибору правильної версії файлу hello.html.

<p align="center">
<img src="Screenshots/ (59).png" alt="(59)"/>
</p>

Завершення процесу перебазування за допомогою git add та git rebase --continue, з подальшим переглядом оновленої історії комітів.

<p align="center">
<img src="Screenshots/ (60).png" alt="(60)"/>
</p>

Переключення на гілку main та об'єднання змін з гілки style, що успішно виконано в режимі fast-forward.

<p align="center">
<img src="Screenshots/ (61).png" alt="(61)"/>
</p>

Перехід до батьківського каталогу та клонування репозиторію work у нову директорію home.

<p align="center">
<img src="Screenshots/ (62).png" alt="(62)"/>
</p>

Перехід до склонованого репозиторію home та перегляд його вмісту і історії комітів.

<p align="center">
<img src="Screenshots/ (63).png" alt="(63)"/>
</p>

Перегляд інформації про віддалений репозиторій 'origin' та налаштування відстеження гілок.

<p align="center">
<img src="Screenshots/ (64).png" alt="(64)"/>
</p>

Перегляд локальних та віддалених гілок за допомогою команд git branch та git branch -a.

<p align="center">
<img src="Screenshots/ (65).png" alt="(65)"/>
</p>

Перехід до директорії work для внесення змін в оригінальний репозиторій.

<p align="center">
<img src="Screenshots/ (66).png" alt="(66)"/>
</p>

Модифікація файлу README шляхом додавання нового рядка "(changed in origin)".

<p align="center">
<img src="Screenshots/ (67).png" alt="(67)"/>
</p>

Фіксація змін у файлі README з відповідним комітом у оригінальному репозиторії.

<p align="center">
<img src="Screenshots/ (68).png" alt="(68)"/>
</p>

Перехід до клонованого репозиторію home та оновлення даних з віддаленого репозиторію за допомогою git fetch.

<p align="center">
<img src="Screenshots/ (69).png" alt="(69)"/>
</p>

Об'єднання змін з віддаленого репозиторію за допомогою git merge origin/main та перевірка актуальності версії через git pull.

<p align="center">
<img src="Screenshots/ (70).png" alt="(70)"/>
</p>

Налаштування відстеження віддаленої гілки style та перегляд всіх гілок репозиторію за допомогою git branch -a.

<p align="center">
<img src="Screenshots/ (71).png" alt="(71)"/>
</p>

Клонування репозиторію work у новий голий репозиторій work.git для використання як спільного сховища.

<p align="center">
<img src="Screenshots/ (72).png" alt="(72)"/>
</p>

Додавання нового віддаленого репозиторію з назвою shared, що вказує на створений голий репозиторій work.git.

<p align="center">
<img src="Screenshots/ (73).png" alt="(73)"/>
</p>

Модифікація файлу README додаванням рядка про зміни та надсилання до спільного репозиторію.

<p align="center">
<img src="Screenshots/ (74).png" alt="(74)"/>
</p>

Створення коміту зі змінами в README та надсилання змін до віддаленого репозиторію shared за допомогою git push.

<p align="center">
<img src="Screenshots/ (75).png" alt="(75)"/>
</p>

Налаштування відстеження віддаленої гілки style та перегляд всіх гілок репозиторію за допомогою git branch -a.

<p align="center">
<img src="Screenshots/ (71).png" alt="(71)"/>
</p>

Клонування репозиторію work у новий голий репозиторій work.git для використання як спільного сховища.

<p align="center">
<img src="Screenshots/ (72).png" alt="(72)"/>
</p>

Додавання нового віддаленого репозиторію з назвою shared, що вказує на створений голий репозиторій work.git.

<p align="center">
<img src="Screenshots/ (73).png" alt="(73)"/>
</p>

Модифікація файлу README додаванням рядка про зміни та надсилання до спільного репозиторію.

<p align="center">
<img src="Screenshots/ (74).png" alt="(74)"/>
</p>

Створення коміту зі змінами в README та надсилання змін до віддаленого репозиторію shared за допомогою git push.

<p align="center">
<img src="Screenshots/ (75).png" alt="(75)"/>
</p>

Перехід до каталогу home, додавання нового віддаленого репозиторію shared та налаштування відстеження гілки main. Отримання останніх змін через git pull.

<p align="center">
<img src="Screenshots/ (76).png" alt="(76)"/>
</p>

Запуск git daemon для створення локального Git-сервера та клонування репозиторію через протокол git:// в нову директорію network_work.

<p align="center">
<img src="Screenshots/ (77).png" alt="(77)"/>
</p>
