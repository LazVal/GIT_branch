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
### _3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта_
```
git checkout bug_report
touch BugReport_structure
vim BugReport_structure
```
### _4. Запушить структуру багрепорта на внешний репозиторий_
```
add .
git commit -m "BugReport_structure"
git push
```
### _5. Вмержить ветку Bag Reports в Main_
```
git checkout main
git merge bug_report
```
### _6. Запушить main на внешний репозиторий._
```
git push origin main
```
### _7. В ветке CheckLists набросать структуру чек листа._
```
git checkout CheckLists
git touch Checklists_structure
vim Checklists_structure
```
### _8. Запушить структуру на внешний репозиторий._
```
add .
git commit -m "Checklists_structure"
git push
```
### _9. На внешнем репозитории сделать Pull Request ветки CheckLists в main._
### _10. Синхронизировать Внешнюю и Локальную ветки Main._
```
git checkout main
git pull
```