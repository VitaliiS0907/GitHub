### <u>Общее руководство по ДЗ</u>

**1) Создайте текстоовый файл как в первом ДЗ по Terminal**
- cat > GitHub1.md

**2) Сценарий перенесите в этот файл**
- ctrl + c *(скопировать текст задания - Windows)*
- ctrl + v *(вставить текст задания - GitBash)*
- ctrl + c *(закрыть и сохранить файл - GitBash)*

**3) На против каждого действия - напишите команду в GitBash**


### <u>JSON</u>

**4) Создать внешний репозиторий c названием JSON**
- Находясь на главной странице профиля в GitHub перейти в раздел ***"Repositories"***
- Нажать на кнопку ***"New"***
- Указать название ***"JSON"*** в поле ***"Repository name"***
- Нажать на чек-бокс ***"Add a README file"***
- Нажать на кнопку ***"Create repository"***

**5) Клонировать репозиторий JSON на локальный компьютер**
- Находясь на странице созданного репозитория ***"JSON"*** нажать кнопку ***"Code"***
- Скопировать адрес репозитория *(HTTPS)*
- Перейдя в GitBash ввести следующую команду:
  - git clone <https://github.com/VitaliiS0907/JSON.git>

**6) Внутри локального JSON создать файл *“new.json”***
- touch new.json

**7) Добавить файл под гит**
- git add new.json

**8) Закоммитить файл**
- git commit -m "new file"

**9) Отправить файл на внешний GitHub репозиторий**
- git push

**10) Отредактировать содержание файла *“new.json”* - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON**
- vim new.json
  - i
  - содержимое: 
  <pre>
```json
{
     "person_surname": "Shevchenko",
     "person_name": "Vitalii",
     "person_patronymic": "Andriiovych",
     "person_age": 26,
     "number_of_domestic_animals": 1,
     "desired_future_salary_USD": {
                                       "junior": 600,
                                       "middle": 1500,
                                        "senior": 3000
      }

}
```
 </pre>

-
    - нажать кнопку Esc
    - **:**
    - x
    - Enter

**11) Отправить изменения на внешний репозиторий**
- git commit -am new.json
- git push

**12) Создать файл *preferences.json***
- touch preferences.json

**13) В файл *preferences.json* добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON**
- vim preferences.json
  - i
  - содержимое: 
  <pre>
```json
{
    "favorite_movie": "Interstellar, The Proposal, Rocky",
    "favorite_series": "Friends",
   "favorite_food": "Mashed potatoes, Salad Olivie, Roasted Chicken",
    "favorite_season": "Spring, Summer",
   "side_you_would_like_to_visit": "Czech, Norway, USA"
}
```
 </pre>

-
    - нажать кнопку Esc
    - **:**
    - x
    - Enter
    
**14) Создать файл *sklls.json* добавить информацию о скиллах которые будут изучены на курсе в формате JSON**
- vim sklls.json
  - i
  - содержимое: 
  <pre>
```json
{
    "Basic_theory": {
        "Definition and understanding of what testing is": "SDLC, STLC, bug reports, documentation, types, methods, areas of testing, etc"
    },
    "Client-server_architecture": "Basic concepts and features",
    "HTTP": ["Server request methods", "Server response codes", "Structures of requests and responses"],
    "JSON_XML": "structure and features",
    "API": "Postman (JS, API autotests)",
    "DevTools": "Google Chrome, FireFox",
    "Mobile_Testing": {
        "feature": "iOS, Android",
        "Tools": "XCode, Android Studio, ADB, Proxy and VPN"
    },
    "Packet_analyzer_or_Sniffer": "Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android",
    "Linux_Terminal": {
        "Commands": "pwd, mkdir, ls -la, mv, cp, cd, cat/>/>>, grep/grep -r . >, find/find . -name, tail/tail -f, ssh, curl"
    },
    "GitHub": {
        "Commands": "git add ., git commit, git push, git pull, git branch, git checkout, git merge"
    },
    "SQL": {
        "Commands": "Create, Delete, Drop, Insert Into, Select, From, Where, Join"
    },
    "Agile_software_development": "Scrum, Kanban",
    "Test_Design_Techniques": {
        "Techniques": "Equivalence Classes, Boundary Values, Combinatorial Techniques (Pairwise, Orthogonal, Basic Choice, Every Choice), States and Transitions"
    },
    "Stress_Testing": "Jmeter",
    "Python": "Learning the basics"
}
```
 </pre>

-
    - нажать кнопку Esc
    - **:**
    - x
    - Enter

**15) Отправить сразу 2 файла на внешний репозиторий**
- git add . 
- git commit -m "two json"

**16) На веб интерфейсе создать файл *bug_report.json***
- находясь в репозитории JSON нажать кнопку "Add file" -> "Create new file"
- в поле "Name your file" укахать имя файла "bug_report.json"

**17) Сделать Commit changes (сохранить) изменения на веб интерфейсе**
- нажать кнопку "Commit changes" (указав Commit message: bug_report.json)

**18) На веб интерфейсе модифицировать файл *bug_report.json*, добавить баг репорт в формате JSON**
- Из списка выбрать и перейти на страницу файла "bug_report.json"
- [Нажать на изображение карандаша для редактирования](https://ibb.co/FK8WtFH)
- Внести изменения

**19) Сделать Commit changes (сохранить) изменения на веб интерфейсе**
- Нажать кнопку Commit changes
- Указав Commit message: bug_report.json
- Нажать кнопку Commit changes для сохранения изменений

**20) Синхронизировать внешний и локальный репозиторий JSON**
- git pull 
- git push

### <u>XML</u>

**21) Создать внешний репозиторий c названием XML**
- Находясь на главной странице профиля в GitHub перейти в раздел ***"Repositories"***
- Нажать на кнопку ***"New"***
- Указать название ***"XML"*** в поле ***"Repository name"***
- Нажать на чек-бокс ***"Add a README file"***
- Нажать на кнопку ***"Create repository"***

**22) Клонировать репозиторий XML на локальный компьютер**
- Находясь на странице созданного репозитория ***"XML"*** нажать кнопку ***"Code"***
- Скопировать адрес репозитория *(HTTPS)*
- Перейдя в GitBash ввести следующую команду:
  - git clone <https://github.com/VitaliiS0907/XML.git>

**23) Внутри локального XML создать файл *“new.xml”***
- touch new.xml

**24) Добавить файл под гит**
- git add new.xml

**25) Закоммитить файл**
- git commit -m new.xml

**26) Отправить файл на внешний GitHub репозиторий**
- git push

**27) Отредактировать содержание файла *“new.xml”* - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML**
- vim new.xml
  - i
  - содержимое: 

<pre>
<person_info>
    <surname>Shevchenko</surname>
    <name>Vitalii</name>
    <patronymic>Andriiovych</patronymic>
    <age>26</age>
    <number_of_domestic_animals>1</number_of_domestic_animals>
    <desired_future_salary_USD>
        <junior>600</junior>
        <middle>1500</middle>
        <senior>3000</senior>
    </desired_future_salary_USD>
</person_info>
</pre>

-
    - нажать кнопку Esc
    - **:**
    - x
    - Enter


**28) Отправить изменения на внешний репозиторий**
-  git commit -am new.xml

**29) Создать файл *preferences.xml***
- touch preferences.xml

**30) В файл *preferences.xml* добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML**
- vim preferences.xml
  - i
  - содержимое: 

<pre>
<preferences>
    <favorite_movie>
        <film_1>Interstellar</film_1>
        <film_2>The Proposal</film_2>
        <film_3>Rocky</film_3>
    </favorite_movie>
    <favorite_series>Friends</favorite_series>
    <favorite_food>
        <dish_1>Olivie Salad</dish_1>
        <dish_2>Mashed potatoes</dish_2>
        <dish_3>Roasted Chicken</dish_3>
    </favorite_food>
    <favorite_season>
        <season_1>Spring</season_1>
        <season_2>Summer</season_2>
    </favorite_season>
    <side_you_would_like_to_visit>
        <country_1>Czech</country_1>
        <country_2>Norway</country_2>
        <country_3>USA</country_3>
    </side_you_would_like_to_visit>
</preferences>
</pre>

  - нажать кнопку Esc
    - **:**
    - x
    - Enter

**31) Создать файл *sklls.xml* добавить информацию о скиллах которые будут изучены на курсе в формате XML**
- vim sklls.xml
  - i
  - содержимое: 

<pre>
<skills>
  <Basic_theory>
        <section_1>Definition and understanding of what testing is</section_1>
        <section_2>SDLC</section_2>
        <section_3>STLC</section_3>
        <section_4>Bug reports</section_4>
        <section_5>Documentation</section_5>
        <section_6>Types</section_6>
        <section_7>Methods</section_7>
        <section_8>Areas of testing</section_8>
        <section_n>etc</section_n>
  </Basic_theory>
  <Client-server_architecture>Basic concepts and features</Client-server_architecture>
  <HTTP>
        <HTTP_1>Server request methods</HTTP_1>
        <HTTP_2>Server response codes</HTTP_2>
        <HTTP_3>Structures of requests and responses</HTTP_3>
  </HTTP>
  <JSON_XML>Structure and feature</JSON_XML>
  <API>Postman (JS, API autotests)</API>
  <DevTools>Google Chrome, FireFox</DevTools>
  <Mobile_Testing>
      <Feature_1>iOS</Feature_1>
      <Feature_2>Android</Feature_2>
      <Tools_1>XCode</Tools_1>
      <Tools_2>Android Studio</Tools_2>
      <Tools_3>ADB</Tools_3>
      <Tools_4>Proxy and VPN</Tools_4>
  </Mobile_Testing>
  <Packet_analyzer_or_Sniffer>Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android</Packet_analyzer_or_Sniffer>
  <Linux_Terminal>
      <Commands>pwd, mkdir, ls -la, mv, cp, cd, cat/>/>>, grep/grep -r . >, find/find . -name, tail/tail -f, ssh, curl</Commands>
  </Linux_Terminal>
  <GitHub>
      <Commands>git add ., git commit, git push, git pull, git branch, git checkout, git merge</Commands>
  </GitHub>
  <SQL>
      <Commands>Create, Delete, Drop, Insert Into, Select, From, Where, Join</Commands>
  </SQL>
  <Agile_software_development>Scrum, Kanban</Agile_software_development>
  <Test_Design_Techniques>
      <Techniques_1>Equivalence Classes</Techniques_1>
      <Techniques_2>Boundary Values</Techniques_2>
      <Techniques_3>Combinatorial Techniques (Pairwise, Orthogonal, Basic Choice, Every Choice)</Techniques_3>
      <Techniques_4>States and Transitions</Techniques_4>
  </Test_Design_Techniques>
  <Stress_Testing>Jmeter</Stress_Testing>
  <Python>Learning the basics</Python>
</skills>
</pre>

  - нажать кнопку Esc
    - **:**
    - x
    - Enter

**32) Сделать коммит в одну строку**
- git add . && git commit -m "two xml"

**33) Отправить сразу 2 файла на внешний репозиторий**
- git push

**34) На веб интерфейсе создать файл *bug_report.xml***
- находясь в репозитории XML нажать кнопку "Add file" -> "Create new file"
- в поле "Name your file" указать имя файла "bug_report.xml"

**35) Сделать Commit changes (сохранить) изменения на веб интерфейсе**
- нажать кнопку "Commit changes" (указав Commit message: bug_report.xml)

**36) На веб интерфейсе модифицировать файл *bug_report.xml*, добавить баг репорт в формате XML**
- Из списка выбрать и перейти на страницу файла "bug_report.xml"
- [Нажать на изображение карандаша для редактирования](https://ibb.co/FK8WtFH)
- Внести изменения

**37) Сделать Commit changes (сохранить) изменения на веб интерфейсе**
- Нажать кнопку Commit changes
- Указав Commit message: bug_report.xml
- Нажать кнопку Commit changes для сохранения изменений

**38) Синхронизировать внешний и локальный репозиторий XML**
- git pull 
- git push

### <u>TXT</u>

**1) Создать внешний репозиторий c названием TXT**
- Находясь на главной странице профиля в GitHub перейти в раздел ***"Repositories"***
- Нажать на кнопку ***"New"***
- Указать название ***"TXT"*** в поле ***"Repository name"***
- Нажать на чек-бокс ***"Add a README file"***
- Нажать на кнопку ***"Create repository"***

**2) Клонировать репозиторий TXT на локальный компьютер**
- Находясь на странице созданного репозитория ***"TXT"*** нажать кнопку ***"Code"***
- Скопировать адрес репозитория *(HTTPS)*
- Перейдя в GitBash ввести следующую команду:
  - git clone <https://github.com/VitaliiS0907/TXT.git>

**3) Внутри локального TXT создать файл *“new.txt”***
- touch new.txt

**4) Добавить файл под гит**
- git add new.txt

**5) Закоммитить файл**
- git commit -m "new.txt"

**6) Отправить файл на внешний GitHub репозиторий**
- git push

**7) Отредактировать содержание файла *“new.txt”* - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT**
- vim new.txt
  - i
  - содержимое: 
  <pre>
```txt
  surname: Shevchenko
  name: Vitalii
  patronymic: Andriiovych
  age: 26
  number of domestic animals: 1
  desired future salary (USD): 
    - junior: 600
    - middle: 1500
    - senior: 3000
```
 </pre>

- нажать кнопку Esc
  - **:**
  - x
  - Enter

**8) Отправить изменения на внешний репозиторий**
- git commit -am new.txt

**9) Создать файл *preferences.txt***
- touch preferences.txt

**10) В файл *"preferences.txt”* добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT**
- vim preferences.txt
  - i
  - содержимое: 
  <pre>
```txt
  favorite movie: Interstellar, The Proposal, Rocky
  favorite series: Friends
  favorite food: Mashed potatoes, Salad Olivie, Roasted Chicken
  favorite season: Spring, Summer
  side you would like to visit: Czech, Norway, USA
```
 </pre>

- нажать кнопку Esc
  - **:**
  - x
  - Enter
  
**11) Создать файл *sklls.txt* добавить информацию о скиллах которые будут изучены на курсе в формате TXT**
- vim sklls.txt
  - i
  - содержимое: 
  <pre>
```txt
  Basic theory: Definition and understanding of what testing is, SDLC, STLC, bug reports, documentation, types, methods, areas of testing, etc.
  Client-server architecture: Basic concepts and features
  HTTP: Server request methods, Server response codes, "Structures of requests and responses
  JSON, XML: structure and features
  API: Postman (JS, API autotests)
  DevTools: Google Chrome, FireFox
  Mobile Testing: Feature - iOS, Android,
                  Tools - XCode, Android Studio, ADB, Proxy and VPN
  Packet analyzer or Sniffer: Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android
  Linux-Terminal: pwd, mkdir, ls -la, mv, cp, cd, cat/>/>>, grep/grep -r . >, find/find . -name, tail/tail -f, ssh, curl
  GitHub: git add ., git commit, git push, git pull, git branch, git checkout, git merge
  SQL: Create, Delete, Drop, Insert Into, Select, From, Where, Join
  Agile software development: Scrum, Kanban
  Test Design Techniques: Equivalence Classes, Boundary Values, Combinatorial Techniques (Pairwise, Orthogonal, Basic Choice, Every Choice), States and Transitions
  Stress Testing: Jmeter
  Python: Learning the basics
```
 </pre>

-
    - нажать кнопку Esc
    - **:**
    - x
    - Enter

**12) Сделать коммит в одну строку**
- git add . && git commit -m "two txt"

**13) Отправить сразу 2 файла на внешний репозиторий**
- git push

**14) На веб интерфейсе создать файл *bug_report.txt***
- находясь в репозитории XML нажать кнопку "Add file" -> "Create new file"
- в поле "Name your file" указать имя файла "bug_report.txt"

**15) Сделать Commit changes (сохранить) изменения на веб интерфейсе**
- нажать кнопку "Commit changes" (указав Commit message: bug_report.txt)

**16) На веб интерфейсе модифицировать файл *bug_report.txt*, добавить баг репорт в формате TXT**
- Из списка выбрать и перейти на страницу файла "bug_report.txt"
- [Нажать на изображение карандаша для редактирования](https://ibb.co/FK8WtFH)
- Внести изменения

**17) Сделать Commit changes (сохранить) изменения на веб интерфейсе**
- Нажать кнопку Commit changes
- Указав Commit message: bug_report.txt
- Нажать кнопку Commit changes для сохранения изменений

**18) Синхронизировать внешний и локальный репозиторий TXT**
- git pull 
- git push