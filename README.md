# -VIM

# Замена всех слов на другие 
        %s/word1/word2/g         - где g - заменять все всхождения а не только первое 
        dd - удалитьь строку
        shift + y - корирование выделеннной строки
        shift + р - вставка выделеннной строки        
        dd - удалить строку

# Git Hub

#set git config values #Авторизация

        git pull - Стянуть

        git checkout - переключение веток
        
        git config --global user.name "ваше имя"

        git config --global user.email "ваше_мыло@gmail.com"

        git config --global github.user ник

        git config --global github.token your_token_here#Основные команды гит:

        git clone [url]

        git add . - Добавить все (. - Обозначает текущий каталог со всем содержимым)

        git commit -m "mesage" - Создать комит

        git push - отправить

        git rn file_name - удалить из репозитория

        git branch branch_name - создать ветку
        
        git merge - сливает ветку с текущей
        
        git status - получить статус
        
         
# Git-Dumper (сКАЧИВАЕМ .GIT И вытягиваем с него файлы)

https://github.com/arthaud/git-dumper
https://github.com/internetwache/GitTools/tree/master/Dumper        
        
        git-dumper http://cat.htb/.git dump

        https://github.com/internetwache/GitTools/blob/master/Extractor/extractor.sh

        ./extractor.sh dump git-ext
        
