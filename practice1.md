# Инструкция по работе с GIT

## Основные понятия и термины

**Репозиторий**- Хранилище файлов,поддерживающее версионность.

**Контроль версий**-Практика,которая позволяет отслеживать изменения исходного кода и управлять ими.

_**Контроль версий необходим,чтобы:**_
* Хранить разные версии проекта.
* Возвращаться к разным версиям проекта.

**Система контроля**-Это реализованная возможность замены информации с использованием сохраненных версий.

_**!Git хранит не файлы целиком,а отличия между ними.**_ Это позволяет экономить память.

_**Git самая популярная система конроля версий,но не единственная.**_

Автор программы- **Линус Торвальдс**, создатель **ОС Linux**.

**Markdown**-Язык разметки,который позволяет форматировать текст.

# Основные команды GIT

**git --version** -проверка текущей версии программы. Если гит установлен, увидим его текущуюю версию

**git init** -инициализация репозитория;указываем папку,в которой git начнет отслеживать изменения. В папке создается скрытая папка .git .

**git status** - показывает текущее состояние гита, есть ли изменения которые нужно сохранить.

**git log** - журнал изменений; Перед переключением версии файлов в git используйте команду *git log* , чтобы увидеть количество изменений.

**git checkout** - переключение между версиями; Для работы нужно указать не только интересующий вас коммит , но и вернуться в тот где работаем, при помощи команды *git checkout master*.

## Команды сохранения GIT

**git add** добавляет содержимое рабочего каталога в индекс, для последующего коммита. Эта команда дается после добавления файлов. Писать название полностью необязательно,терминал дозаполнит автоматически.

**git commit** зафиксировать или сохранить. Флаг *-m* добавляет комментарий. Например: _**git commit -m"Добавили строку"**_

# Команды GIT с использованием веток

**git branch** - выводит на экран список веток и показывает на какой ветке сейчас находимся(показывает *).

**git branch name** - создает новую ветку ( из ветки *master*).

**git branch -d name** - удаляет ветку.

**git log --graph** - выводит дерево коммитов.

**git merge name** - слияние веток. Слияние происходит с вызываемой веткой в ту где находимся сейчас.

**git merge --abort** - откатить слияние.

# МЕМЫ

![типичный программист](tipical.jpg)

![Скопировал код](copy.jpg)



