# Подсказки по командной строке

## Команды

Авторизация в Git:
```sh
git config --global user.name "Name"
git config --global user.email "email"
```

Инициализация репозитория:
```sh
git init
```

Команда статуса ветки:
```sh
git status
```

Добавить отслеживание изменений:
```sh
git add <file_name>
```

Добавить коментарий:
```sh
git commit -m "text"
```
Журнал изменений в развернутом виде:
```sh
git log
```

Журнал изменений в кратком виде:
```sh
git log --oneline
```

Переход по версиям сохранений:(требуются первые 4 символа идентификатора изо лога)
```sh
git checkout "идентификатор"
```

Команда отображения текущей дериктории
```sh
pwd
```

Листинг текущей директории 
Windows:
```sh
dir
```
Linux, MacOs:
```sh
ls
```

Перемещение по веткам:
```sh
git checkout <имя ветки>
```

Отображение всех веток:

```sh
git branch
```

Вернуться к последнему состояний изменений:
```sh
git checkout master or main
```

Создание новой ветки:
```sh
git branch <branch_name>
```

Удаление ветки:
```sh
git branch -d <branch_name>
```
Слияние веток:
```sh
git merge <branch_name>
```

Отчистка терминала:
```sh
clear
```

## Работа с удаленными репозиториями.

### Чтобы добавить репозиторий на гит хаб нужно:
 1. Создать на гитхаб аккаунт.
 2. Создать новый репозиторий.

### Далее загрузить репозиторий с локального компьютера на гитхаб.
```sh
 1. git remote add origin https://github.com/IlyaMonya/Home_work-4.03.24.git (ссылка на аккаунт)
 2. git branch -M main (задать основную ветку)
 3. git push -u origin main (загружает проект на гитхаб)
```

Далее изменения в гитхаб с локального репозитория вноситься командой:
```sh
git push
```

Чтобы загрузить изменения с гитхаб в локальный репозиторий команда:
```sh
git pull
```

## Работа с чужим репозиторием
```
На сайте находим нужный репозиторий.

Нажимаем кнопку fork.

Далее вводим команду git clone <ссылка на репозиторий>. Клонируем репозиторий на локальный компьютер.

Создаем ветку с предполагаемыми изменениями.

Производим изменения в этой ветке.

Отправляем на свой аккаунт по средствам команды git push

Далее появляется возможность сделать pull request(запрос на вытягивание)



