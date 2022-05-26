---
## Front matter
title: "Индивидуальный проект 5 этап"
subtitle: "*дисциплина:операционные системы*"
author: "Бондаренко Елизавета Валентиновна"

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

Научиться делать персональный проект

# Задание

1. Сделать записи для персональных проектов.
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору.
- Языки научного программирования.

# Выполнение индивидуального проекта

1. Меняем в папке home/projects названия разделов. (рис. [-@fig:001]) (рис. [-@fig:002])

![персональный проект](image/1.jpg){ #fig:001 width=70% }

![projects](image/2.jpg){ #fig:002 width=70% }

Переходим в папку content/progect и меняем информацию. В первую графу "Информатика" я добавила информацию об этой теме (рис. [-@fig:003])

![информатика](image/3.jpg){ #fig:003 width=70% }

Во вторую графу "Операционные системы" я добавила информацию об этой теме (рис. [-@fig:004])

![операционные системы](image/4.jpg){ #fig:004 width=70% }

В третью графу "Информационная безопасность" я добавила информацию об этой теме (рис. [-@fig:005])

![информационная безопасность](image/5.jpg){ #fig:005 width=70% }

2. Делаем пост о прошедшей неделе (рис. [-@fig:006])

![пост о прошедшей неделе](image/6.jpg){ #fig:006 width=70% }

3. Делаем пост по теме "Языки научного программирования" (рис. [-@fig:007])

![Языки научного программирования](image/7.jpg){ #fig:007 width=70% }

# Выводы

В ходе выполнения 5 этапа индивидуального проекта я научилась делать записи для персональных проектов.



::: {#refs}
:::
