# Homework Branches

| Задание | Решение |
|---------|---------|
|1. На локальном репозитории сделать ветки для:||
|- Postman|`git branch` *Postman*|
|- Jmeter|`git branch` *Jmeter*|
|- Checklists|`git branch` *Checklists*|
|- Bag Reports|`git branch` *Bag_reports*|
|- SQL|`git branch` *SQL*|
|- Charles|`git branch` *Charles*|
|- Mobile testing|`git branch` *Mobile_testing*|
|2. Запушить все ветки на внешний репозиторий|`git push -u origin --all` |
|3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта|`git checkout` *Bag_Reports* &nbsp; ; &nbsp; `vim` *Structure_br.txt*|
|4. Запушить структуру багрепорта на внешний репозиторий|`git add .` &nbsp; ; &nbsp; `git commit -m` *'Sctructure_br.txt'* &nbsp; ; &nbsp; `git push -u origin` *Bag_reports*|
|5. Вмержить ветку Bag Reports в Main|`git checkout` *master* &nbsp; ; &nbsp; `git merge` *Bag_Reports*|
|6. Запушить main на внешний репозиторий.|`git push -u origin` *master*|
|7. В ветке CheckLists набросать структуру чек листа.|`git checkout` *Checklists* &nbsp; ; &nbsp; `vim` *Structure_cl.txt*|
|8. Запушить структуру на внешний репозиторий|`git add .` &nbsp; ; &nbsp; `git commit -m` 'Structure_cl.txt' &nbsp; ; &nbsp; `git push -u origin` *Checklists* &nbsp; ; &nbsp; `git checkout` *master* &nbsp; ; &nbsp; `git merge` *Checklists*|
|9. На внешнем репозитории сделать Pull Request ветки CheckLists в main|На внешнем репозитории нажать на **Compare & pull request** при необходимости оставить комментарий и нажать **Create pull request** дальше смержить нажав на **Merge pull request** и для подтверждения действия нажать **Confirm merge**|
|10. Синхронизировать Внешнюю и Локальную ветки Main|`git fetch` &nbsp; ; &nbsp; `git pull` &nbsp; ; &nbsp; `git push -u origin` *master*|