## Инструкция 

* git branch -m старое_название_ветки новое_название_ветки - переименовать ветки
* git branch - посмотреть список веток в репозитории
git branch -m старое_название_ветки новое_название_ветки - переименовать ветки

* git branch <название ветки> - создать новую ветку
git branch -m старое_название_ветки новое_название_ветки - переименовать ветки

* git branch -d <название ветки > - удалить ветку

* git chekout - переход к другой ветке

* git merge <название ветки> - слияние ветки в текущую

## Информация о работе с удаленными репозиториями

* git remote - список настроенных удаленных репозиториев

* git remote -v - для просмотра адреса для чтения и записи, привязанных к репозиторию
* git remote add "shortname" "url" - добавление удаленного репозитория и присвоение ему имени (Shortname)
* git fetch "remote-name"- связь с указанным удаленным проектом и слияние данных указанного проекта с вашими.
* git push "remote-name" "branch-name" - отправка данных в удаленный репозиторий
* git remote show - получение большего обьема информации об одномиз удаленных репозиториев
* git remote rename - переименование репозитория