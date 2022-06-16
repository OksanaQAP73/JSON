# JSON
1. Создать внешний репозиторий c названием JSON:
	```
	1.1 Зайти в свой аккаунт на сайте https://github.com/ 
	1.2 Выбрать вверху пункт меню Repositories
	1.3 Нажать в правом верхнем углу кнопку NEW
	1.4 Вписать в поле Repository name название нового репозитория JSON
 	1.5 Сделать его публичным
 	1.6 Поставить галочку рядом с Add a README file
 	1.7 Нажать внизу на кнопку Creat repository
	```
2. Клонировать репозиторий JSON на локальный компьютер:
	```
	2.1 Нажать на кнопку справа Code
	2.2 Выбрать HTTPS
	2.3 Скопировать ссылку на репозиторий, расположена ниже
	2.4 Зайти в Terminal
	2.5 Зайти в папку в которой будем рабоать -> ~ Oxana$ cd documents/30QAGroup/
	2.6 Создать папку в которой будем работать -> 30QAGroup Oxana$ mkdir GitHub
	2.7 Зайти в созданную папку -> 30QAGroup Oxana$ cd GitHub/
	2.8 Создать на ПК клон репозитория c GitHub -> GitHub Oxana$ git clone https://github.com/OksanaQAP73/JSON.git
	```
3. Внутри локального JSON создать файл “new.json”:
	```
	3.1 Зайти в папку JSON на ПК -> GitHub Oxana$ cd json
	3.2 Создать файл new.json -> json Oxana$ touch new.json
	```
4. Добавить файл под гит:
	```
	4.1 json Oxana$ git add new.json
	```
5. Закоммитить файл:
	```
	5.1 json Oxana$ git commit -m "add the first file"
	```
6. Отправить файл на внешний GitHub репозиторий:
	```
	6.1 json Oxana$ git push
	```
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON:
	```
	7.1 json Oxana$ vim new.json
	7.2 Нажать кнопку I -> зашли в режим редактирования
	7.3 Пишем информацию о себе в формате JSON:
	```
		```json
		{
		"name": "Oksana",
		"age": "46",
		"animals": "Don't have animals",
		"salary": "200 000 rub"
		}
		```

	```
	7.4 Нажать для выхода Esc -> :wq
	```
8. Отправить изменения на внешний репозиторий:
	```
	8.1 json Oxana$ git add new.json
	8.2 json Oxana$ git commit -m "information about me"
	8.3 json Oxana$ git push
	```
9. Создать файл preferences.json:
	```
	9.1 json Oxana$ touch preferences.json
	```
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON:
	```
	10.1 json Oxana$ vim preferences.json
	10.2 Нажать кнопку I -> зашли в режим редактирования
	10.3 Написать информацию о своих предпочтениях в формате JSON:
	```    
	```json
		{
		"Любимый фильм": "Амели",
		"Любимый сериал": "Удивительная миссис Мейзел",
		"Любимая еда": "Жареная картошка с творогом, Борщ, Окрошка, Креветки",
		"Любимое время года": "Лето",
		"Страна которую хотели бы посетить": "Новая Зеландия"
		}
	```

	```
   	10.4 Нажать для выхода Esc -> :wq
	```
11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON:
	```
	11.1 json Oxana$ cat >> sklls.json
	```
	```json
		{
		"skills": "Terminal, Git, Testing QA, JS"
		}
	```

	```
	11.2 Нажать Ctrl + D для выхода из режима редактирования и сохранения файла
	```
12. Отправить сразу 2 файла на внешний репозиторий:
	```
	12.1 json Oxana$ git add preferences.json sklls.json
	12.2 json Oxana$ git commit -m 'Add 2 new files'
	12.3 json Oxana$ git push
	```
13. На веб интерфейсе создать файл bug_report.json:


