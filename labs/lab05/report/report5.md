---
## Front matter
title: "Отчёт по лабораторной работе №5"
subtitle: "Дисциплина: Архитектура компьютера.Операционные системы"
author: "Буриева Шахзода Акмаловна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Изучение и освоение менеджера паролей на pass,основных свойств и работа с ним и репозиторием.

# Выполнение лабораторной работы

Сперва на виртуальную машину установила pass пароль с помощью команды dnf install pass pass-otp.

Далее настраиваю эту программу с помощью команды dnf install gopass.

Приступила к настройке pass и gopass.Для этого просмотрела список ключей GPG, И если нет ключа,то создала новый ключ GPG. 

Далее инициализировала хранилище.

Создала структуру git.

Создала адрес репозитория на хостинге(предворительно создав репозиторий).

Для синхронизации ввела команды pass git pull and pass git push.

Т.к изменения сделаны непосредственно на файловой системе,то вручную закоммитила и выложила изменения.

Для взаимодействия с браузером используется интерфейс native messaging,поэтому установила программу,обеспечивающая этот интерфейс.

Добавила новый пароль,введя команду pass insert.

Отобразила пароль для указанного имени файла.

Заменила существующий пароль.

Установила дполнительное программное обеспечение.

Далее установила шрифты.

Установила бинарный файл.Скрипт определяет архитектуру процессора и операционную систему и скачивает необходимый файл.

Создала свой репозиторий для конфигурационных файлов на основе шаблона.

Инициализировала chezmoi с моим репозиторием dotfiles.

Запустив chezmoi diff проверила,какие изменения внесёт chezmoi в домашний каталог.

Меня устраивают изменения,внесённые chezmoi,поэтому запускаю chezmoi apply -v.

На втрой машине инициализировала chezmoi c моим репозиторием dotfiles. 

Запустив chezmoi diff проверила,какие изменения внесёт chezmoi в домашний каталог.

Меня устраивают изменения,внесённые chezmoi,поэтому запускаю chezmoi apply -v.

Также можно вызвать инструмент слияния, чтобы объединить изменения между текущим содержимым файла, файлом в вашей рабочей копии и измененным содержимым файла

При существующем каталоге chezmoi можно получить и применить последние изменения из вашего репозитория.

Далее устанавливаю свои dotfiles на новый компьютер с помощью одной команды.

Извлекла последние изменения из репозитория и применила их одной командой.

Извлекла последние изменения из своего репозитория и посмотрела, что изменится, фактически не применяя изменения.

Выполнила chezmoi git pull -- --autostash --rebase && chezmoi diff.

Я довольна изменениями,поэтому применила их.

Автоматически зафиксировала и отправила изменения в репозиторий.


# Выводы

Изучила и освоила менеджера паролей на pass, рассмотрела основные свойства и научилась с помощью этого работать с ним и репозиторием.


# Список литературы{.unnumbered}

::: {#refs}
:::
