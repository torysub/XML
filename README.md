# XML

 1. Создать внешний репозиторий c названием XML.
 
 *New*
 
 ![image](https://user-images.githubusercontent.com/105368491/173537087-0bedb087-b2cc-4090-8996-38c1477e3cf6.png)

 *Name: XML*

 ![image](https://user-images.githubusercontent.com/105368491/173537700-60aeb51c-7155-43b5-afb4-a185b33c9263.png)

 *Public*

 ![image](https://user-images.githubusercontent.com/105368491/173537406-70aba0ea-d4b9-4c13-a27e-3840046ae68d.png)

 *Check "Add a README file"*

 ![image](https://user-images.githubusercontent.com/105368491/173537467-f70060d9-cd07-4ac7-9c64-1863ab6da833.png)

 *Press "Create repository"*

 ![image](https://user-images.githubusercontent.com/105368491/173537533-e08952e4-ffe0-4461-806b-a898d01c9f5c.png)
 
 2. Клонировать репозиторий XML на локальный компьютер. 
 
 `git clone https://github.com/torysub/XML.git`

 3. Внутри локального XML создать файл “new.xml”. 
 
 `touch new.xml`

 4. Добавить файл под гит. 
 
 `git add new.xml`

 5. Закоммитить файл. 
 
 `git commit -m "Added the new.xml"`

 6. Отправить файл на внешний GitHub репозиторий. 
 
 `git push`

 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML. 
 
 `vim new.xml`
 
 ```
 <?xml version="1.0" encoding="UTF-8" ?>
<person>
  <first_name>Viktoriya</first_name>
  <middle_name>Alexandrovna</middle_name>
  <last_name>Subbotina</last_name>
  <age>31</age>
  <pets>
    <cat>1</cat>
    <dog>1</dog>
  </pets>
  <salary>1000$</salary>
</person>
```

*Нажать **"Esc"** :wq **"Enter"***

 8. Отправить изменения на внешний репозиторий. 
 
 ```
 git commit -am "new information added"
 
 git push
  ```

 9. Создать файл preferences.xml 
 
 `touch preferences.xml`
 
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML. 
 
 `vim preferences.xml`
 
 ```
<?xml version="1.0" encoding="UTF-8" ?>
<root>
  <favorite_movie>Interstellar</favorite_movie>
  <favorite_TV_series>Friends</favorite_TV_series>
  <favorite_food>pasta</favorite_food>
  <favorite_food>potato mash</favorite_food>
  <favorite_food>shish kebab</favorite_food>
  <favorite_food>salad</favorite_food>
  <favorite_time_year>summer</favorite_time_year>
  <country>Australia</country>
</root>
```

*Нажать **"Esc"** :wq **"Enter"***

 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML 
 
 `vim skills.xml`
 
 ```
 <?xml version="1.0" encoding="UTF-8" ?>
<skills>
  <HTTP>client-server architecture</HTTP>
  <HTTP>HTTP methods of requests to the server</HTTP>
  <HTTP>HTTP server response codes</HTTP>
  <HTTP>HTTP request and Response structures</HTTP>
  <database>SQL</database>
  <database>Redis</database>
  <database>Postgres</database>
  <API>Postman</API>
  <API>JS</API>
  <API>API autotests</API>
  <sniffing>Charles</sniffing>
  <sniffing>Fidler</sniffing>
  <DevTools>Google Chrome</DevTools>
  <DevTools>FireFox</DevTools>
  <methodology>SCRUM</methodology>
  <basic_testing_theory>testing</basic_testing_theory>
  <basic_testing_theory>bug reports</basic_testing_theory>
  <basic_testing_theory>documentation</basic_testing_theory>
  <basic_testing_theory>SDLC</basic_testing_theory>
  <basic_testing_theory>STLC</basic_testing_theory>
  <data_exchange_format>JSON</data_exchange_format>
  <data_exchange_format>XML</data_exchange_format>
  <mobile_testing>iOS</mobile_testing>
  <mobile_testing>Android</mobile_testing>
  <building_applications>Android Studio</building_applications>
  <building_applications>XCode</building_applications>
  <working_in_the_terminal>GitBush</working_in_the_terminal>
  <working_in_the_terminal>GitHub</working_in_the_terminal>
  <load_testing>Jmeter</load_testing>
</skills>
```

*Нажать **"Esc"** :wq **"Enter"***

 12. Сделать коммит в одну строку. 
 
 `git add . && git commit -m "Added preferences.xml and skills.xml files"`

 13. Отправить сразу 2 файла на внешний репозиторий. 
 
 `git push`

 14. На веб интерфейсе создать файл bug_report.xml.
 
 *Add file*
 
 ![image](https://user-images.githubusercontent.com/105368491/173547630-f65152d1-a8c9-45a9-9784-91cb0fe57f98.png)
 
 *Create new file*

 ![image](https://user-images.githubusercontent.com/105368491/173547705-25232379-1a4a-4ceb-be33-46589b7f2530.png)
 
 Name: bug_report.xml
 
 ![image](https://user-images.githubusercontent.com/105368491/173546359-28d56a82-8e25-485f-8d43-0697bc8eeeb2.png)

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 *Commit New File*
 
 ![image](https://user-images.githubusercontent.com/105368491/173547987-4c6cfcf8-f89a-4776-a77b-e44155869d72.png)
 
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 
 *Choose bug_report.xml*
 
 ![image](https://user-images.githubusercontent.com/105368491/173546767-847486f9-48a2-44b6-87e8-c8abf71401ef.png)
 
 *Edit this file*
 
 ![image](https://user-images.githubusercontent.com/105368491/173548367-e77b2c3d-2b21-4223-862c-e97b951de466.png)
 
 ```
 <?xml version="1.0" encoding="UTF-8" ?>
<root>
  <Bug-ID>1</Bug-ID>
  <Title>Поле ввода &#x27;Введите номер телефона&#x27; не позволяет ввести цифры после нажатия на кнопу &#x27;Войти по номеру телефона&#x27;</Title>
  <Project>Сайт магазина &#x27;Malina&#x27;</Project>
  <STR>1. Открыть страницу входа</STR>
  <STR>2. Нажать на кнопку &#x27;Войти по номеру телефона&#x27;</STR>
  <STR>3. Начать вводить цифры  от 0 до 9 в поле &#x27;Введите номер телефона&#x27;</STR>
  <AR>Невозможно ввести цифры от 0 до 9  в поле ввода &#x27;Введите номер телефона&#x27; </AR>
  <ER>В поле &#x27;Введите номер телефона&#x27; возможно внести 10 цифр номера телефона от 0 до 9</ER>
  <Environment>
    <OS>Windows 10 PRO 64-bit operating system, x64 processor</OS>
    <Browser>Google Chrome Version 102.0.5005.63 (Official build), (64 bit)</Browser>
  </Environment>
  <Severity>Major</Severity>
  <Priority>Medium</Priority>
  <Status>New</Status>
  <Author>Виктория Субботина</Author>
</root>
```
 
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 *Commit changes*
 
 ![image](https://user-images.githubusercontent.com/105368491/173548519-61eca3cc-0e31-4a0d-aba1-d3ecd04da1db.png)

 19. Синхронизировать внешний и локальный репозиторий XML.
 
 `git pull`
