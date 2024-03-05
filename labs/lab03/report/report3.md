---
## Front matter
title: "Отчёт по лабораторной работе №3"
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

Целью данной работы является обучение оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

1. Сделать отчёт по предыдущей лабораторной работе в формате Markdown.
2. В качестве отчёта предоставить отчёты в 3 форматах: pdf, docx и md (в архиве, поскольку он должен содержать скриншоты, Makefile и т.д.

# Теоретическое введение

Markdown- это простой язык разметки, используемый для создания форматированного текста (например, HTML) с помощью текстового редактора. Он позволяет добавлять к тексту базовое форматирование, используя символы, известные и доступные на всех клавиатурах.
Чтобы создать заголовок, надо использовать знак #.
Чтобы задать для текста полужирное начертание, надо заключить его в двойные звёздочки.
Чтобы задать для текста курсивное начертание, надо заключить его в одинарные звёздочки.
Чтобы задать для текста полужирное и курсивное начертание, надо заключить его в тройные звёздочки.
Блоки цитирования создаются с помощью символа >.
Markdown поддерживает как встраивание фрагментов кода в предложение, так и их разме- щение между предложениями в виде отдельных ограждённых блоков. Ограждённые блоки кода — это простой способ выделить синтаксис для фрагментов кода.
В Markdown вставить изображение в документ можно с помощью непосредственного указания адреса изображения.

# Выполнение лабораторной работы
1. Изучила язык разметки Markdown.
2. Изучила структуру отчётов по лабораторным работам согласно требованиям.
3. Сделала отчёт по лабораторной работе №2 в трёх форматах(pdf, docx и md),записав видео.

# Выводы

Научилась оформлять отчёты с помощью легковесного языка разметки Markdown и сделала отчёт по лабораторной работе №2.

# Список литературы{.unnumbered}

::: {#refs}
:::
