<img src="img/red.png" width="50" height="50">

# cpp-lab-4
# Лабораторная работа №4 (Automata)

## Задачи

> Разработать класс `Automata` (автомат), являющийся упрощённой моделью автомата по продаже горячих напитков.
Изучить принцип использования автомата по продаже горячих напитков (чай, кофе, молоко и т.д.) и описать его работу в виде диаграммы состояний.

- Создать перечислимый тип `STATES` для задания состояний автомата
- Создать класс `Automata`, включить в него переменные:
  - `cash` - для хранения текущей суммы; 
  - `menu` - массив строк названий напитков (может подгружаться из файла); 
  - `prices` - массив цен напитков (соответствует массиву `menu`); 
  - `state` - текущее состояние автомата;

Включить в класс `Automata` следующие методы:

- конструктор
- on() - включение автомата;
- off() - выключение автомата;
- coin() - занесение денег на счёт пользователем;
- printMenu() - отображение меню с напитками и ценами для пользователя;
- printState() - отображение текущего состояния для пользователя;
- choice() - выбор напитка пользователем;
- check() - проверка наличия необходимой суммы;
- cancel() - отмена сеанса обслуживания пользователем;
- cook() - имитация процесса приготовления напитка;
- finish() - завершение обслуживания пользователя.

Список методов может быть изменён по желанию разработчика.

Предлагается следующая диаграмма состояний (state diagram), отражающая смену состояний и вызовы методов класса

<img src="img/automata.png">


## Список участников/веток

|  ФИО              | Имя ветки |
|-------------------|-----------|
|Альперович	Вадим | b1|
|Андрющенко	Александр|b2|
|Аросланкин	Артем|b3|
|Востряков	Дмитрий|b4|
|Горбачева	Арина|b5|
|Горшкова	Екатерина|b6||
|Доненко	Денис|b7|
|Исупова	Мария|b8|
|Кислицына	Анастасия|b9|
|Куклин	Максим|b10|
|Лесин	Николай|b11|
|Макридин	Максим|b12|
|Максимов	Антон|b13|
|Малинин	Василий|b14|
|Мартиросян	Елизавета|b15|
|Мурзаев	Роман|b16|
|Сазанов	Дмитрий|b17|
|Седунов	Илья|b18|
|Сиднева	Анастасия|b19|
|Ситникова	Владислава|b20|
|Слесарева	Василина|b21|
|Смольникова	Полина|b22|
|Тюлин	Владислав|b23|
|Филиппова	Марина|b24|
|Черноземова	Дарья|b25|
|Чернышев	Константин|b26|
|Черняев	Ярослав|b27|


## Алгоритм выполнения работы

Для выполнения работы необходимо:

1. Выполнить *fork* репозитария в свой аккаунт.
1. Выполнить клонирование репозитария из своего аккаунта к себе на локальную машину (`git clone`).
1. Создать ветку **git** с индивидуальным номером (`git branch имя_ветки`).
1. Сделать ветку активной (`git checkout имя`).
1. Необходимо разместить как исходные файлы с решениями задач, поместив **cpp** файлы в **src**, а заголовочные - в **include**. 
1. Добавить файлы в хранилище (`git add`).
1. Выполнить фиксацию изменений (`git commit -m "комментарий"`).
1. Отправить содержимое ветки в свой удаленный репозитарий (`git push origin имя_ветки`).
1. Создать пул-запрос в репозитарий группы и ждать результата от **Travis-CI**.
