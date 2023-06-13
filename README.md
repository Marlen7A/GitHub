# GitHub
 ### __1. На локальном репозитории сделать ветки для:__ 
 - Postman 
 - Jmeter
 - CheckList
 - Bag Reports
 - SQL
 - Charles
 - Mobile testing
   + `git branch Postman`
   + `git branch Jmeter`
   + `git branch Check_List`
   + `git branch Bag_Reports`
   + `git branch SQL`
   + `git branch Charles`
   + `git branch Mobile_testing`
### __2. Запушить все ветки на внешний репозиторий.__ 
 `git push origin --all`
### __3. В ветке Bag reports сделать текстовый документ со структурой баг репорта.__ 
 `git checkout Bag_Reports`
 `vim Bag_Reports.txt`
Нажать __i__
`ID:
Severity: 
Priority: 
Status: 
Title: 
Project: 
Step 1. 
Step 2. 
OS: 
Browser: 
Component:
Actual result: 
Expected result: 
Attachments: 
Author:`
Нажать __ESC"__:x __"Enter"__
### __4. Запушить структуру багрепорта на внешний репозиторий.__ 
`git add . && git commit -m "add Bag_Reports.txt" && git push`
### __5. Вмержить ветку Bag Reports в Main.__ 
`git checkout main`
`git merge Bag_Reports`
### __6. Запушить мain на внешний репозиторий.__ 
`git add . && git commit -m "merge Bug report to master" && git push`
### __7. В ветке CheckLists набросать структуру чек листа.__ 
 `git checkout CheckList`
 `vim CheckList.txt`
Нажать __i__
`D:
Title:
Precondition:
Steps_to_reproduce:
Expected_result:
Status:
Author:`
Нажать __ESC"__:x __"Enter"__
### __8. Запушить структуру на внешний репозиторий.__ 
`git add . && git commit -m "add  CheckList.txt" && git push`
### __9. На внешнем репозитории сделать Pull Request ветки CheckLists в main.__ 
На вебе  - *Открыть* [GitHub](https://github.com)  войти в нужный репозиторий, нажать __Compare & pull request__ возле ветки __CheckList__ затем нажать __Create pull request__ ,__Merge pull request__,__Confirm merge__
### __10. Синхронизировать Внешнюю и Локальную ветки Main.__ 

