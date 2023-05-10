# Git | Homework_2 | GitHub_branches

___
___

1. На локальном репозитории сделать ветки для:

- Postman - git branch Postman
- Jmeter - git branch Jmeter
- CheckLists - git branch CheckLists
- Bag_Reports - git branch Bag_Reports
- SQL - git branch SQL
- Charles - git branch Charles
- Mobile_testing - git branch Mobile_testing

2. Запушить все ветки на внешний репозиторий

>git push -u origin Postman Jmeter CheckLists Bug_Reports SQL Charles Mobile_testing

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

>Переходи в ветку: git checkout Bug_Reports

>Создаём файл: touch Bug_reports.txt

>Вносим изменения: vim, i

```
"ID"
"Title"
"Precondition"
"Steps To Rreproduce"
"Actual Results"
"Expected Results"
"Severity"
"Priority"
"Envoirement"
"Attachments"
"Status"
```
>Сохраняем и выходим: esc, :, w, q.

4. Запушить структуру багрепорта на внешний репозиторий

>git add Bug_reports.txt

>git commit -m "add bug_reports"

>git push

5. Вмержить ветку Bug Reports в Main

>git checkout main

>git merge Bug_Reports

6. Запушить main на внешний репозиторий.

>git push -u origin main

7. В ветке CheckLists набросать структуру чек листа.

>Меняем ветку: git checkout CheckLists

>Создаём файл: touch CheckLists.txt

>Вносим изменения: vim CheckLists.txt

>Нажать "i" вводить текст

```
Short cheklist:
"ID"
"Title"
"Status"
```
```
Extended checklist:
"ID"
"Title"
"Precondition"
"Test steps"
"Expected Result"
"Аctual Result"
"Envoirement"
"Atachment"
"Bug link"
"Status"
```

>Cохранить и выйти: "esc" ":wq"

8. Запушить структуру на внешний репозиторий

>git add CheckLists.txt

>git commit -m "add CheckLists"

>git push

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

  >На web-интерфейсе перейти в ветку CheckLists 

  >Compare & pull request - Сreate pull request

10. Синхронизировать Внешнюю и Локальную ветки Main

>git checkout main

>git pull

___
___

