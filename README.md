<image src="https://www.virusov-net.com/wp-content/uploads/2011/08/System-Preferences.png" alt="Setings command">

```# HI!!!```

# GIT SETTINGS

Команда для создания имени которое будет отображаться в подписи ко всем изменениям в проекте

```$ git config --global user.name "kinomagnum"```

Команда для создания email которое будет отображаться в подписи ко всем изменениям в проекте

```$ git config --global user.email "kondratqa@yandex.ru"```

Команда для того чтобы убедиться что все настройки приминились

```$ git config --global --list```

Команда для для правильного окончания строк

```git config --global core.autocrlf true```
```git config --global core.safecrlf warn```
```git config --global core.quotepath off```


Команда для установки имени ветки по умолчанию main

```git config --global init.defaultBranch main```

Команда для вызова справки GIT
Git даст подробную подсказку по всем доступным командам, если выполнить команду

```git help -g```

Git даст подсказку по конкретной команде, если ввести в терминале

```git help config```


Команда для создания локального репозитория  

```git init```

Команда для того, чтобы узнать, является ли файл README.md отслеживаемым или не отслеживаемый

```git status```

Команда для добавления файла README.md в отслеживаемые файлы

```git add README.md```

Команда для создания коммита и подпись коммита

```git commit -m "Initial commit"```

# WORKING WITH HISTORY

Чтобы посмотреть историю проекта надо ввести

```git log --oneline```

Команда для исправление ошибки подписи в коммите при помощи флага

```git commit --amend -m "cheange README"```

Добавление нового фаайла в репозитолрии в отслеживаемые

```git add -A```

Команда для пееремещения по коммитам

```git checkout 1a5a7de```

Команда для переключения из ранее созданных коммитов в актуальное состояние проекта

```git checkout main```

---------------------------------------------------------------------

команда которая позволяет увидеть свой ssh ключ

```cat ~/.ssh/id_ed25519.pub```

связка локального и удаленного репозитория

```git remote add origin git@github.com:Kondratqa/remoutRepo.git```;

```git remote -v``` ; - проверка связки локального репозитория с виртуальными

Отправка данных с локального репозитория в виртуальный

```git push -u origin main# repo```\


Команда для клонирования репозитория на компьютер

```git clone git@github.com:Kondratqa/Kino.git```

Команда для просмотра веток в проекте

```git branch```

Команда для создания ветки

```git branch kino```

Команда для переключеение на ветку

```git checkout kino```

Командля для слияния веток 

```git merge master```









<image src="https://www.virusov-net.com/wp-content/uploads/2011/08/System-Preferences.png" alt="Setings command">
