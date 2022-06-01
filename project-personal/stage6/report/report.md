---
## Front matter
title: "Индивидуальный проект 6 этап"
subtitle: "*дисциплина:операционные системы"
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

Переводить информацию на англ язык

# Задание

1. Сделать поддержку английского и русского языков.
2. Разместить элементы сайта на обоих языках.
3. Разместить контент на обоих языках.
4. Сделать пост по прошедшей неделе.
5. Добавить пост на тему по выбору (на двух языках).

# Выполнение лабораторной работы

Изменяю все файлы и добавляю на свой сайт информацию о себе на двух языках  (рис. [-@fig:001]) (рис. [-@fig:002]) (рис. [-@fig:003])

![инф на двух языках](image/1.png){ #fig:001 width=70% }

![инф на двух языках](image/2.png){ #fig:002 width=70% }

![инф на двух языках](image/3.png){ #fig:003 width=70% }

Далее пишу пост по прошедшей неделе (рис. [-@fig:004])

![пост о неделе](image/4.png){ #fig:004 width=70% }

А также пишу пост на тему по выбору, я взяла тему - Java (рис. [-@fig:005])(рис. [-@fig:006])

![пост по Java](image/5.png){ #fig:005 width=70% }

![пост по Java](image/6.png){ #fig:006 width=70% }

Вот итоговый вид сайта и посты(рис. [-@fig:007])(рис. [-@fig:008])(рис. [-@fig:009])

![биография](image/7.png){ #fig:007 width=70% }

![skills](image/8.png){ #fig:008 width=70% }

![постs](image/9.png){ #fig:009 width=70% }

# Выводы

В процессе выполнения данной лабораторной работы я научилась делать сайт на двух языках

# Список литературы{.unnumbered}

::: {#refs}
:::
