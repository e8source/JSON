# JSON
Work with GIT, gitbash

 1. Создать внешний репозиторий c названием JSON.
 2. Клонировать репозиторий JSON на локальный компьютер. 
      
        git clone git@github.com:e8source/JSON.git
 3. Внутри локального JSON создать файл “bio.json”. 
 
        touch bio.json
 4. Добавить файл под гит. 
 
        git add bio.json
 5. Закоммитить файл. 
 
        git commit -m "Add bio.json"
 6. Отправить файл на внешний GitHub репозиторий.  
 
        git push
 7. Отредактировать содержание файла “new.json” - написать информацию о себе в формате JSON (ФИО, возраст, локация, роль). 
 
        nano bio.json
 8. Отправить изменения на внешний репозиторий. 
 
        git add bio.json && git commit -m "Edit new.json" && git push
 9. Создать файл preferences.json 
 
        touch preferences.json 
 10. В файл preferences.json добавить информацию о своих предпочтениях в формате JSON (музыка, игра, фильм, сериал). 
 
         nano preferences.json
 
 11. Создать файл skills.json добавить информацию о скиллах в формате JSON.
 
         touch skills.json
         nano skills.json 
 12. Отправить сразу 2 файла на внешний репозиторий.
   
         git add .
         git commit -m "Add preferences.json and skills.json"
         git push
 13. На веб интерфейсе создать файл bug_report.json.
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 17. Синхронизировать внешний и локальный репозиторий JSON.
 
         git pull
