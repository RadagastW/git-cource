#Git

``` git
git --version
```

``` git
git --help
```

``` git
clear
```

`dir` - список папок и файлов
`cd <folder>` - сменить папку
`cd ..` - сменить на дочернюю папку
`mkdir <name>` - создать папку

Инициализация репозитория:
``` git
git init
```

Текущий статус:
``` git
git status
```

Добавление файла / всех файлов в отслеживаемые:
``` git
git add <file>
git add .
```

Удаление файла из отслеживаемых:
``` git
git rm --cached <file>
```

Добавление коммита:
``` git
git commit -m "init: git-cource"
```

Для добавления файлов и папок в игнорируемые записываем их в файл `.gitignore`

Просмотр ветки:
``` git
git branch
```

Создать ветку:
``` git
git branch <name>
```

Создать ветку и перейти на нее:
``` git
git checkout -b <name>
```

Удалить ветку:
``` git
git branch -D <name>
```

Перейти на ветку:
``` git
git checkout <name>
```

Объединить ветку с указанной:
``` git
git merge <name>
```

Имя и email пользователя git:
``` git
git config user.name
git config user.email
```

Сменить имя и email пользователя git:
``` git
git config user.name "name"
git config user.email "email"
```

Привязать удаленный репозиторий в GitHub к локальному:
``` git
git remote add origin git@github.com:RadagastW/git-cource.git
```

Отправить изменения в GitHub:
``` git
git push -u origin master
```

Отправить изменения:
``` git
git push
```

Получить изменения:
``` git
git pull
```

Перейти в папку с ssh-ключами:
``` git
cd ~/.ssh
```

Скопировать ключ:
``` git
clip < ~/.ssh/id_rsa.pub
```

Клонировать проект в локальную папку:
``` git
$ git clone https://github.com/RadagastW/git-cource.git
```