# Задаем глобально имя пользователя
git config --global user.name "Sergey"

# Задаем глобально адрес электронной почты
git config --global user.email "insigonet@gmail.com"

# Инициализация проекта
git init

# Добавление файлов в репозиторий
git add .	// Всех файлов
git add index.html		// Только index.html

# Статус файлов
git status

# Делаем коминт
git commit -m "first commit"

# Определение удаленного репозитория
git remote add origin https://github.com/insigonet/sass-master-template

# Загружаем репозиторий на GitHub
git push -u origin master



** -------------- Дополнительно ---------------
# URL
https://habrahabr.ru/post/273897/


# Выести настройки конфигурации
git config --list

# Отобразить зарегистрирований репозиторий
git remote -v

# Удалить регистрацию удаленного репозитория
git remote rm origin

# Клонировать
git clone https://github.com/jquery/jquery.git

# Удалить определение удаленного репозитория
git remote remove origin


# Steps to remove directory
git rm -r --cached FolderName
git commit -m "Removed folder from repository"
git push origin master
