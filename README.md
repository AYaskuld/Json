## Задача ##

**1. Создать внешний репозиторий c названием JSON.**  
**2. Клонировать репозиторий JSON на локальный компьютер.**  
**3. Внутри локального JSON создать файл “new.json”.**  
**4. Добавить файл под гит.**  
**5. Закоммитить файл.**  
**6. Отправить файл на внешний GitHub репозиторий.**  
**7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.**  
**8. Отправить изменения на внешний репозиторий.**  
**9. Создать файл preferences.json**  
**10. В файл preferences.json” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.**  
**11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.**  
**12. Сделать коммит в одну строку.**  
**13. Отправить сразу 2 файла на внешний репозиторий.**  
**14. На веб интерфейсе создать файл bug_report.json.**  
**15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**  
**16. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.**  
**17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**  
**18. Синхронизировать внешний и локальный репозиторий JSON.**  

## Решение ##  

**1. Создать внешний репозиторий c названием JSON.**  
```//создал репозиторий на с названием JSON```

**2. Клонировать репозиторий JSON на локальный компьютер.**  
```bash
git clone //вставляю SSH ссылку из репозитория
```
**3. Внутри локального JSON создать файл “new.json”.**  
```bash
touch new.json
```
**4. Добавить файл под гит.**  
```bash
git add --a
```
**5. Закоммитить файл.**  
```bash
git commit -m create_new.json
```
**6. Отправить файл на внешний GitHub репозиторий.**  
```bash
git pull
```
**7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.**  
```bash
nano new.json
```
добавляю информацию
жму ctrl+x, y, enter

**8. Отправить изменения на внешний репозиторий.**  
```повторяю п.4 и п.5```  

**9. Создать файл preferences.json**  
**10. В файл preferences.json” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.**  
```bash
nano preferences.json 
```
ввожу необходимые данные
ctrl+x, y, enter

**11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.**  
```bash
nano skills.json
```
ддобавляю содержимое
ctrl+x, y, enter

**12. Сделать коммит в одну строку.**  
```bash
git commit --a|git commit -m add_pred_skills
```
**13. Отправить сразу 2 файла на внешний репозиторий.**  
```bash
git push
```
**14. На веб интерфейсе создать файл bug_report.json.**  
```//создаю```  
**15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**  
```//делаю коммит```  
**16. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.**  
```//добавляю данные```  
**17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**  
```//опять коммит```  
**18. Синхронизировать внешний и локальный репозиторий JSON.**  
```bash
git pull
```
