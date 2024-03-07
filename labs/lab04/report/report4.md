---
## Front matter
title: Отчёт по лабораторной работе №4"
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

Цель данной работы является получение навыков правильной работы с репозиториями git.
# Задание

1. Выполнить работу для тестового репозитория.
2. Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.


# Выполнение лабораторной работы

Установила git-flow на Fedora

На Node.js базируется программное обеспечение для семантического версионирования и общепринятых коммитов,поэтому установила ее также.

Для работы с Node.js добавила каталог с исполняемыми файлами, устанавливаемыми yarn, в переменную PATH.

Запустила pnpm.

Перелогинилась.

Данной программой  форматировала коммиты.

При этом устанавила скрипт git-cz, который мы и будем использовать для коммитов.

Данной программой создала логи.

Создала репозитория git.

Подключила репозиторий к github.

Создайте репозиторий на GitHub. Для примера назвала его git-extended.

Сделала первый коммит и выложила на github.

Конфигурация для пакетов Node.js.

Заполнила несколько параметров пакета.

1. Название пакета.
2. Лицензия пакета.

Сконфигурила формат коммитов. Для этого добавим в файл package.json команду для формирования коммитов

Добавила новые файлы

Выполнила коммит

Отправила на github

Инициализировала git-flow

Проверила, что я на ветке develop.

Загрузила весь репозиторий в хранилищею

Установила внешнюю ветку как вышестоящую для этой ветки.

Создала релиз с версией 1.0.0.

Создала журнал изменений.

Добавила журнал изменений в индекс.

Залила релизную ветку в основную ветку.

Отправила данные на github.

Создала релиз на github. Для этого будем использовать утилиты работы с github.

Создала ветку для новой функциональности.

Далее, продолжила работу c git как обычно.

По окончании разработки новой функциональности следующим шагом объединила ветку feature_branch c develop.


Создала релиз с версией 1.2.3.

Обновила номер версии в файле package.json. Установила её в 1.2.3.

Создала журнал изменений.

Добавила журнал изменений в индекс.

Залила релизную ветку в основную ветку.

Отправила данные на github.

Создала релиз на github с комментарием из журнала изменений.


# Выводы
Получили навыки правильной работы с репозиториями git.

# Список литературы{.unnumbered}

::: {#refs}
:::
