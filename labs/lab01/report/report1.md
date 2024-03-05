---
## Front matter
title: "Отчёт по лабораторной работе №1"
subtitle: "Дисциплина: Архитектура компьютера. Операционные системы"
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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Выполнение лабораторной работы

Всю практическую часть этой работы я проделывала на Ubuntu(можно посмотреть в моем отчёте за первый семестр),думаю это аналогично fedora.В видео,выложенном на ютубе и rutube всё показала с случаем на fedora.
Однако хочу напомнить основные шаги для установки ВМ с операционной системой семейства линукс:
1. Сперва надо установить Oracle vm Virtual Box и образ дистрибутива,нужного нам.
2. Потом надо создать ВМ,настроив для нее виртуальный диск,память,тип ОС.
3. В итоге надо запустить ВМ и настроить ее под себя.

# Ответы на контрольные вопросы

1. Учетная запись пользователя хранит информацию об имени пользователя и пароль.
2. Для справки по команде после нее нужно добить ключ -h cat -h для перемещения по файловой системе cd для просмотра содержимого каталога ls для получения информации о размере каталога du для создания и удаления файлов соответсвенно cat,rm и для каталогов mkdir,rm -r права задаются командой chmod +x somefile(это команда разрешит выполнение для всех пользователей). для просмотра истории команд. 
3. Фауйловая система-это способ организации файлов и папок для работы с ними. 
4. С помощью команды findmnt. 5)Любой,даже зависший процесс можно прервать с помощью клавишкомбницации Ctrl+C 

# Выводы

Приобрели практические навыки установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Список литературы{.unnumbered}

::: {#refs}
:::
