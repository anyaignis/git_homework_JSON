# JSON
4. Создать внешний репозиторий c названием JSON
5. Клонировать репозиторий JSON на локальный компьютер		    

>  $ git clone git@github.com:anyaignis/JSON.git

6. Внутри локального JSON создать файл “new.json”

>$ touch new.json

7. Добавить файл под гит

>$ git add new.json

8. Закоммитить файл

>$ git commit -m "new file added"

9. Отправить файл на внешний GitHub репозиторий

>$ git push

10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

>$ cat >> new.json
>[
>{
>  "surname"  : "Жовтобрух",
>  "first name" : "Анна",
> "patronymic" : "Алексеевна"
>},
>{
>  "age" : 28
>},
>{
>   "number_of_pets" : 1
>},
>{
   "desired_salary" : 500
}
]
ctrl+c

11. Отправить изменения на внешний репозиторий

>$ git add new.json
$ git commit -m "modified"
$ git push

12. Создать файл preferences.json
$ touch preferences.json

13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
$ cat >> preferences.json
[
{
        "favorite_movie" : "Джентельмены",
        "favorite_serial" : "Во_все_тяжкие",
        "favorite_food" : "суши"
},

{
        "favorite_time_of_year" : "autumn",
        "country_to_visit" : "Norway"
}
]
ctrl+c

14. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
cat >> skills.json
[
{
	"skill_1": "testing_theory",
	"skill_2": "bug_reporting",
	"skill_3": "test_case",
	"skill_4": "check_list",
	"skill_5": "mobile_testing"
}, 
{
	"client_server_1": "http_methods",
	"client_server_2": "http_statuses",
	"client_server_3": "json_xml_structures",
	"client_server_4": "api_testing"
}, 
{
	"tool_1": "postman",
	"tool_2": "charles",
	"tool_3": "fiddler",
	"tool_4": "android_studio",
	"tool_5": "jmeter",
	"tool_6": "xcode",
	"tool_7": "dev_tools"
}, 
{
	"database": "sql",
	"git_bash": "commands"
}
]
ctrl+c

15. Отправить сразу 2 файла на внешний репозиторий
$ git push -u

16. На веб интерфейсе создать файл bug_report.json
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе
18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе
20. Синхронизировать внешний и локальный репозиторий JSON
$ git pull



