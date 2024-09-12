---
## Front matter
title: "Oтчёт по индивидуальному проекту"
subtitle: "Этап 1"
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

Установить Kali Linux в виртуальную машину

# Задание


    Установите дистрибутив Kali Linux в виртуальную машину.
    В качестве среды виртуализации предлагается использовать VirtualBox.
    Сайт Kali Linux: https://www.kali.org/
    Учётные данные по умолчанию:
        логин: root;
        пароль: toor.


# Выполнение лабораторной работы

1. Начнем устанавливать Kali Linux (рис. [-@fig:001])

![Загрузка](photo1.jpg){ #fig:001 width=70% }

2. Откроем готовый файл (рис. [-@fig:002])

![Просмотр установленной программы](photo2.jpg) { #fig:002 width=70% }

# Выводы

В Ходе выполнения этапа номер один, мы научились устанавливать Kali Linux в виртуальную машину

# Список литературы{.unnumbered}

::: {#refs}
:::
