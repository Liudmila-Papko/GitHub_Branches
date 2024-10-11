# GIT Homework 2

#### 1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
```
git branch Postman
git branch Jmeter
git branch CheckLists
git branch BugReports
git branch SQL
git branch Charles
git branch MobileTesting
```
#### 2. Запушить все ветки на внешний репозиторий
```
git push -u origin --all
```
#### 3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта
```
vim Bug_Reports.txt
INSERT (i)
1) ID
2) Date
3) Priority
4) Severity
5) Environment
6) Title
7) Steps
8) Expected result
9) Actual result
10) Attachment
11) Author
12) Status
13) Comments
ESC :wq
```
#### 4. Запушить структуру багрепорта на внешний репозиторий
```
git add Bug_Reports.txt
git commit -m "Add Bug Report"
git push
```
#### 5. Вмержить ветку Bug Reports в Main
```
git checkout main
git merge BugReports
```
#### 6. Запушить main на внешний репозиторий.
```
git push
```
#### 7. В ветке CheckLists набросать структуру чек листа.
```
git checkout CheckLists
vim Checklist.txt
INSERT (i)
1) Name of the product
2) Version
3) Environment
4) Date
5) Title of testing moduls
6) ID
7) List of tests
8) Expected result
9) Status
10 Comment
ESC :wq
```
#### 8. Запушить структуру на внешний репозиторий
```
git add Checklist.txt
git commit -m "Add Check list"
git push
```
#### 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
- перейти на страницу https://github.com/Liudmila-Papko/Skills
- нажать кнопку Compare & pull request
- Add a title
- Нажать Create pull request
- Нажать Merge pull request
- Нажать Confirm merge
#### 10. Синхронизировать Внешнюю и Локальную ветки Main (находимся в main ветке)
```
git pull
```
