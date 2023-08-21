# work-space
git init
git add README.md
git commit -m "first commit" 
git branch -M main 
git remote add origin https://github.com/AlekcKhabirov/-Methed.git
git push -u origin main #запушить
 git remote add origin https://github.com/AlekcKhabirov/-Methed.git
 git branch -M main git push -u origin main #дополнения
 git-config #Действия после установки git посмотреть настройки
  git config --list
  git config --global user.name “имя”
  git config --global user.email “почта”
git config --global core.safecrlf warn 
git config --global core.quotepath off 
git config --global init.defaultBranch main # Ветка по умолчанию windows 
git config --global core.autocrlf true MAC & UNIX 
git config --global core.autocrlf input  
git init  #Действия при инициализации нового репозитория и при работе с ним инициализация git репозитория
git status  #текущее состояние репозитория
git add index.html #добавить в трек (отслеживаемые) файл или папку
git add .  # добавить все файлы из корня в трек
git commit -m "сообщение" #выполнить коммит (сделать слепок) текущего состояния проекта
git log --oneline посмотреть историю коммитов
# Получение изменений с Github
```shell
git pull --rebase
