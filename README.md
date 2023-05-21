# JavaScript Object Notation

 1. Создать внешний репозиторий c названием JSON - `Github Аккаунт в вебе` > _вкладка_ `Repositories` > _кнопка_ `New`
 2. Клонировать репозиторий JSON на локальный компьютер - `git clone https://github.com/XXXXX/JSON.git`
 3. Внутри локального JSON создать файл “new.json”. touch new.json - `touch new.json`
 4. Добавить файл под гит - `git add new.json`
 5. Закоммитить файл - `git commit -m 'add new.json'`
 6. Отправить файл на внешний GitHub репозиторий - `git push`
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON - `vim new.json`
```
{
	"firstname": "Dmitry",
	"lastname": "Romanushkov",
	"age": 27,
	"numberOfPets": 1,
	"futureDesiredSalary": 2000
}
```
 8. Отправить изменения на внешний репозиторий - `git commit -am 'update new.json'` > `git push`
 9. Создать файл preferences.json - `vim preferences.json`
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```
{
	"favoriteFilm": "The Lord Of The Rings",
	"favoriteSerial": "GameOfThrones",
	"favoriteFood": "Pizza",
	"favoriteSeason": "Winter",
	"countryIWouldLikeToVisit": "USA"
}
```
 11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON - `vim skills.json`
```
{
	"skills": [
		"Software testing theory",
		"Test-design techniques",
		"Working with test documentation",
		"Client-server architecture",
		"JSON and XML structure",
		"API testing via Postman",
		"Devtools practice",
		"Git and GitBash practice",
		"Payload testing via Jmeter",
		"Mobile testing",
		"SQL basics",
		"Python basics"
		]
}
```
 12. Отправить сразу 2 файла на внешний репозиторий - `git add .` > `git commit -m 'send 2 files'` > `git push`
 13. На веб интерфейсе создать файл bug_report.json - `Github Аккаунт в вебе` > `Add file` > `Create new file`
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
```
{
  "id": 1,
  "severity": "minor",
  "priority": "low",
  "environment": [
  "Windows 10 home, Chrome 112",
  "iPhone XR, IOS 16.5"
  ],
  "title": "The text hasn't been translated to EN on the 'About us' page",
  "stepsToReproduce": [
    "step 1": "Navigate to site.com",
    "step 2": "Click menu item 'About us'",
    "step 3": "Select EN language",
  ]
  "actualResult": "The text has been translated to EN",
  "expectedResult": "The text hasn't been translated to EN",
  "attachments": "*link to the video*",
  "author": "Poor tester"
}
```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 17. Синхронизировать внешний и локальный репозиторий JSON - `git fetch` - _посмотреть коммиты, произведенные на удаленном репозитории,_ `git pull` - _сгрузить все изменения с удаленного репозитория в локальный._
