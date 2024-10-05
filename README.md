GitHub_HW_1
JSON
1. Создать внешний репозиторий c названием JSON
Заходим на [GitHub](https://github.com/) нажать `+` в `New repository` вводим имя `JSON` нажать `Create repository`

2. Клонировать репозиторий JSON на локальный компьютер
cd  /d/GitHub/new_git_repo 
git clone https://github.com/DenisSuyarkau/JSON.git

3. Внутри локального JSON создать файл “new.json”
`touch new.json`

4. Добавить файл под гит
`git add new.json`

5. Закоммитить файл
`git commit -m "add new file"`

6. Отправить файл на внешний GitHub репозиторий
`git push`

7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON
`vim new.json`
`i` — перейти в режим редактирования

```json
{
	"name": "Suyarkau Dzianis Valentinovicv",
	"age": "38",
	"count_pets": "0",
	"salary": "2500$"
}
```
`esc` `:` `wq`

8. Отправить изменения на внешний репозиторий
`git status` - смотрим какие файлы изменились
`git add new.json` - файл отслеживается
`git commit -m  "wrote information about myself` - снимок текущего состояния файла с комментарием `wrote information about myself`
`git push` - отправляем файл на внешний репозиторий

9. Создать файл preferences.json
`touch preferences.json`

10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON\
`vim preferences.json`
`i` — перейти в режим редактирования

```json
{
	"Favorite movie" : "Three Musketeers",
	"Favorite series" : "Four troopers and a dog",
	"Favorite food" : "Grilled meat",
	"Favorite season" : "Summer",
	"Country i would like to visit" : "Japan"
}
```
`esc` `:` `wq`

11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
`vim skills.json`
`i` — перейти в режим редактирования

```json
{ 
"1" : "Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.д.) SDLC, STLC.",
"2" : "Что такое клиент-серверная архитектура",
"3" : "HTTP Методы запросов на сервер",
"4" : "Коды ответов HTTP сервера",
"5" : "Структуры HTTP запросов и ответов",
"6" : "Что такое JSON, XML. Их структура",
"7" : "Тестирование API через Postman (JS, автотесты API)",
"8" : "Снятие и чтение логов c внешнего сервера",
"9" : "Снифинг http web трафика через Charles и Fiddler",
"10" : "Dev Tools веб браузеров (Google Chrome, FireFox)",
"11" : "VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)",
"12" : "Мобильное тестирование",
"13" : "Особенность iOS, Android, гайдлайны:",
"14" : "Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)",
"15" : "Сборка Android приложений на Android Studio.",
"16" : "ADB (управление андройд девайсами).",
"17" : "Настройка прокси и vpn на iOS и Android.",
"18" : "Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.",
"19" : "Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
"20" : "Основы bash скриптинг, автоматизация рутинных задач на сервере.",
"21" : "Доступ к удалённым серверам.",
"22" : "Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).",
"23" : "База данных Postgres (установка, настройка и использование).",
"24" : "Нереляционная база данных Redis (установка, настройка и использование).",
"25" : "Нагрузочное тестирование в Jmeter.",
"26" : "Методология разработки Scrum.",
"27" : "Техники тест-дизайна (Классы эквивалентности, граничные значения, комбинаторные техники (Попарный, ортогональный, базовый выбор, каждый выбор), состояния и переходы)",
"28" : "Python. (Изучение основ. Создание клиент серверного приложения)"
}```
`esc` `:` `wq`

12. Отправить сразу 2 файла на внешний репозиторий
     `git add preferences.json skills.json`
    или `git add {preferences,skills}.json`

    `git status`
    `git commit -m  "add skills and preferences files"`
    `git push`
     `git add {preferences,skills}.json && git commit -m "add 2 files and commit and push" && git push` - одной командой делаем add, commit, push

13. На веб интерфейсе создать файл bug_report.json
нажать `add new file` затем `create new file` пишем название файла 

14. Сделать Commit changes (сохранить) изменения на веб интерфейсе
в `commit new file` пишем `create bug_report` нажимаем `Commit new file`

15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON
открыть файл, нажать `bug_report.json` нажать `edit this file`

```json
{
	"ID" : "1",
	"Summary" : "",
	"Severity" : "",
	"Steps to reptoduce" : "",
	"Actual Result" : "",
	"Expected Result" : ""
}```
`esc` `:` `wq`

16. Сделать Commit changes (сохранить) изменения на веб интерфейсе
пишем в `Commit changes` `update bug_report`

17. Синхронизировать внешний и локальный репозиторий JSON
`git pull`

 XML
1. Создать внешний репозиторий c названием XML
Заходим на [GitHub](https://github.com/) нажать `+` в `New repository` вводим имя `XML` нажать `Create repository`

2. Клонировать репозиторий XML на локальный компьютер
`cd /d/GitHub/new_git_repo
`git clone https://github.com/DenisSuyarkau/XML.git

3. Внутри локального XML создать файл “new.xml”
`touch new.xml`

4. Добавить файл под гит
`git add new.xml`
`git status`

5. Закоммитить файл
`git commit -m "add new xml file"`

6. Отправить файл на внешний GitHub репозиторий
`git push`

7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML

```xml
<new>
	<name>Suyarkau Dzianis Valentinovich</name>,
        <age>38</age>,
        <count>0</count>,
        <salary>2500$</salary>
</new>```

8. Отправить изменения на внешний репозиторий
`git add new.xml`
`git commit -m  "wrote information about myself"`
`git push`

9. Создать файл preferences.xml
`touch preferences.xml`

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML
`vim preferences.xml`
`i` — перейти в режим редактирования

```xml
<preferences>
	<Favorite_movie>Three Musketeers</Favorite_movie>,
	<Favorite_series>Four troopers and a dog<Favorite_series/>,
	<Favorite_food>Grilled meat</Favorite_food>,
	<Favorite_season>Summe</Favorite_season>",
	<Country_i_would_like_to_visit>Japan</Country_i_would_like_to_visit>
</preferences>

11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
`vim skills.xml`
`i` — перейти в режим редактирования

```xml
<skills>
	<1>Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.д.) SDLC, STLC.</1>,
	<2>Что такое клиент-серверная архитектура</2>
	<3>HTTP Методы запросов на сервер</3>,
	<4>Коды ответов HTTP сервера</4>,
	<5>Структуры HTTP запросов и ответов</5>,
	<6>Что такое JSON, XML. Их структура</6>,
	<7>Тестирование API через Postman (JS, автотесты API)</7>,
	<8>Снятие и чтение логов c внешнего сервера</8>,
	<9>Снифинг http web трафика через Charles и Fiddler</9>,
	<10>Dev Tools веб браузеров (Google Chrome, FireFox)</10>,
	<11>VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)</11>,
	<12>Мобильное тестирование</12>,
	<13>Особенность iOS, Android, гайдлайны:</13>,
	<14>Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)</14>,
	<15>Сборка Android приложений на Android Studio.</15>,
	<16>ADB (управление андройд девайсами).</16>,
	<17>Настройка прокси и vpn на iOS и Android.</17>,
	<18>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.</18>,
	<19>Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)</19>,
	<20>Основы bash скриптинг, автоматизация рутинных задач на сервере.</20>,
	<21>Доступ к удалённым серверам.</21>,
	<22>Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).</22>,
	<23>База данных Postgres (установка, настройка и использование).</23>,
	<24>Нереляционная база данных Redis (установка, настройка и использование).</24>,
	<25>Нагрузочное тестирование в Jmeter.</25>,
	<26>Методология разработки Scrum.</26>,
	<27>Техники тест-дизайна (Классы эквивалентности, граничные значения, комбинаторные техники (Попарный, ортогональный, базовый выбор, каждый выбор), состояния и переходы)</27>,
	<28>Python. (Изучение основ. Создание клиент серверного приложения)</28>
</skills>

12. Сделать коммит в одну строку
`git status`
`git add {pefereces,skills}.xml && git commit -m "add and commit 2 files`

13. Отправить сразу 2 файла на внешний репозиторий
`git status
`git push`

14. На веб интерфейсе создать файл bug_report.xml
нажать `add new file` `create new file` пишем название файла

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе
в `commit new file` пишем `create bug_report` нажимаем `Commit new file`

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML
открыть файл, нажать `bug_report.xml` нажать `edit this file`

```xml
<bug_report>
        <ID>1</ID>,
        <Summary>""</Summary>,
        <Severity>""</Severity>,
        <Steps_to_reptoduce>""</Steps_to_reptoduce>,
        <Actual_Result>""</Actual_Result>,
        <Expected_Result>""</Expected_Result>
</bug_report>
```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе
пишем в `Commit changes` `update bug_report`

18. Синхронизировать внешний и локальный репозиторий XML
`git pull`

 TXT
1. Создать внешний репозиторий c названием TXT
Заходим на [GitHub](https://github.com/) нажать `+` в `New repository` вводим имя `TXT` нажать `Create repository`

 2. Клонировать репозиторий TXT на локальный компьютер\
`cd d/GitHub/new_git_repo
`git clone https://github.com/DenisSuyarkau/TXT.git`

 3. Внутри локального TXT создать файл “new.txt”\
`touch new.txt`

 4. Добавить файл под гит\
`git status`\
`git add new.txt`

 5. Закоммитить файл\
`git commit -m "add new file"`

 6. Отправить файл на внешний GitHub репозиторий\
`git push`

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT\
`vim new.txt`\
`i` — перейти в режим редактирования

```txt
Name: Suyarkau Dzianis Valentinovich
Age: 38
Count_pets: 0
Salary: 2500$
```
`esc` `:` `wq`

 8. Отправить изменения на внешний репозиторий\
`git add new.txt`\
`git commit -m  "wrote information about myself"`\
`git push`

 9. Создать файл preferences.txt\
`touch preferences.txt`

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT\
`vim preferences.txt`\
`i` — перейти в режим редактирования

```txt
Favorite movie : Three Musketeers
Favorite series : Four troopers and a dog
Favorite food : Grilled meat
Favorite season : Summer
Country i would like to visit : Japan
```
`esc` `:` `wq`

 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT\
`vim skills.txt`\
`i` — перейти в режим редактирования

```txt
1 : Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.д.) SDLC, STLC.
2 : Что такое клиент-серверная архитектура
3 : HTTP Методы запросов на сервер
4 : Коды ответов HTTP сервера
5 : Структуры HTTP запросов и ответов
6 : Что такое JSON, XML. Их структура
7 : Тестирование API через Postman (JS, автотесты API)
8 : Снятие и чтение логов c внешнего сервера
9 : Снифинг http web трафика через Charles и Fiddler
10 : Dev Tools веб браузеров (Google Chrome, FireFox)
11 : VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
12 : Мобильное тестирование
13 : Особенность iOS, Android, гайдлайны
14 : Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят)
15 : Сборка Android приложений на Android Studio
16 : ADB (управление андройд девайсами)
17 : Настройка прокси и vpn на iOS и Android
18 : Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android
19 : Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)
20 : Основы bash скриптинг, автоматизация рутинных задач на сервере
21 : Доступ к удалённым серверам
22 : Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)
23 : База данных Postgres (установка, настройка и использование)
24 : Нереляционная база данных Redis (установка, настройка и использование)
25 : Нагрузочное тестирование в Jmeter
26 : Методология разработки Scrum
27 : Техники тест-дизайна (Классы эквивалентности, граничные значения, комбинаторные техники (Попарный, ортогональный, базовый выбор, каждый выбор), состояния и переходы)
28 : Python. (Изучение основ. Создание клиент серверного приложения)
```
`esc` `:` `wq`

 12. Сделать коммит в одну строку
`git status
`git add {preferences,skills}.txt && git commit -m "add and commit 2 files"`

 13. Отправить сразу 2 файла на внешний репозиторий
`git status`
`git push`

 14. На веб интерфейсе создать файл bug_report.txt\
нажать `add new file` `create new file` пишем название файла

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе\
в `commit new file` пишем `create bug_report` нажимаем `Commit new file`

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT\
открыть файл, нажать `bug_report.txt` нажать `edit this file`

```txt
ID : 1
Summary : ""
Severity : ""
Steps to reptoduce : ""
Actual Result : ""
Expected Result : ""Test Data: 20.02.2022
```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.\
пишем в `Commit changes` `update bug_report`
 18. Синхронизировать внешний и локальный репозиторий TXT\
`git pull`

