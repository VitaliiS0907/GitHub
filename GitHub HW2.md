**На локальном репозитории сделать ветки :**
- Postman - git branch Postman
- Jmeter - git branch Jmeter
- CheckLists - git branch CheckLists
- Bag Reports - git branch Bag_Reports
- SQL - git branch SQL
- Charles - git branch Charles
- Mobile testing - git branch Mobile_testing

**Запушить все ветки на внешний репозиторий**
- git push --all

**В ветке Bag Reports сделать текстовый документ со структурой баг репорта**
- git checkout Bag_Reports
- cat > Bag_Reports.txt
- указать структуру 
- нажать ctrl+c

**Запушить структуру багрепорта на внешний репозиторий**
- git add .
- git commit -m "Bug report structure.txt"
- git push -u origin Bag_Reports

**Вмержить ветку Bag Reports в Main**
- git checkout main
- git merge Bag_Reports

**Запушить main на внешний репозиторий**
- git push

**В ветке CheckLists набросать структуру чек листа**
- git checkout CheckLists
- cat > CheckLists.txt
- указать структуру
- нажать ctrl+c

**Запушить структуру на внешний репозиторий**
-bgit add .
- git commit -m "CheckLists structure.txt"
- git push -u origin CheckLists

**На внешнем репозитории сделать Pull Request ветки CheckLists в main**
- находясь на внешнем репозитории нажать на кнопку "Compare & pull request"
- в поле для комментариев указать "merge CheckLists"
- нажать на кнопку "Create pull request"
- нажать на кнопку "Merge pull request"
- нажать на кнопку "Confirm merge"

**Синхронизировать Внешнюю и Локальную ветки Main**
- git checkout main
- git fetch
- git pull