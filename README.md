# GIT_branch
### _GitHub. HW_2_

### _1. На локальном репозитории сделать ветки для:_

- Postman
- Jmeter
- CheckLists
- Bug Reports
- SQL
- Charles
- Mobile testing
```
git branch Postman
git branch Jmeter
git branch CheckLists
...
```
### _2. Запушить все ветки на внешний репозиторий_
```
git push -u origin --all
```
1. В ветке Bag Reports сделать текстовый документ со структурой баг репорта

git checkout bug_report
touch BugReport_structure
vim BugReport_structure

4. Запушить структуру багрепорта на внешний репозиторий

add .
git commit -m "BugReport_structure"
git push

5. Вмержить ветку Bag Reports в Main

git checkout main
git merge bug_report

6. Запушить main на внешний репозиторий.

git push origin main

7. В ветке CheckLists набросать структуру чек листа.

git checkout CheckLists
git touch Checklists_structure
vim Checklists_structure

8. Запушить структуру на внешний репозиторий
add .
git commit -m "Checklists_structure"
git push

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

10. Синхронизировать Внешнюю и Локальную ветки Main

git checkout main
git pull
