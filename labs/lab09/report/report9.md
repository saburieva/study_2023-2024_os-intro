---
## Front matter
title: "Отчёт по лабораторной работе №9"
subtitle: "Дисциплина: Архитектура компьютера"
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

Освоение основных возможностей командной оболочки Midnight Commander. Приоб-
ретение навыков практической работы по просмотру каталогов и файлов; манипуляций
с ними.

# Выполнение лабораторной работы

Изучила информацию о mc, вызвав в командной строке man mc.

Запустила из командной строки mc, изучила его структуру и меню.

Выполнила несколько операций в mc, используя управляющие клавиши (операции с панелями; выделение/отмена выделения файлов, копирование/перемещение файлов, получение информации о размере и правах доступа на файлы и/или каталоги и т.п.)

Выполнила основные команды меню левой (или правой) панели. Оценила степень
подробности вывода информации о файлах.

Используя возможности подменю Файл , выполнила:
* просмотр содержимого текстового файла;
* редактирование содержимого текстового файла (без сохранения результатов
редактирования);
* создание каталога;
* копирование в файлов в созданный каталог

С помощью соответствующих средств подменю Команда осуществила:
* поиск в файловой системе файла с заданными условиями (например, файла
* расширением .c или .cpp, содержащего строку main);
* выбор и повторение одной из предыдущих команд;
* переход в домашний каталог;
* анализ файла меню и файла расширений.

Вызвала подменю Настройки . Освоила операции, определяющие структуру экрана mc
(Full screen, Double Width, Show Hidden Files и т.д.).

Создала текстовой файл text.txt.
 
Открыла этот файл с помощью встроенного в mc редактора.

Вставила в открытый файл небольшой фрагмент текста, скопированный из любого
другого файла или Интернета.

Проделала с текстом следующие манипуляции, используя горячие клавиши:
* Удалила строку текста.
* Выделила фрагмент текста и скопировала его на новую строку.
* Выделила фрагмент текста и перенесла его на новую строку.
* Сохранила файл.
* Отменила последнее действие.
* Перешла в конец файла (нажав комбинацию клавиш) и написала некоторый
текст.
* Перешла в начало файла (нажав комбинацию клавиш) и написала некоторый
текст.
* Сохранила и  закрыла файл.

Далее открыла файл с исходным текстом на некотором языке программирования (например C или Java)

Используя меню редактора, включила подсветку синтаксиса, если она не включена,
или выключила, если она включена.

# Выводы

Освоили основные возможности командной оболочки Midnight Commander. Приобрели навыки практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Список литературы{.unnumbered}

::: {#refs}
:::
