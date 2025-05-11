---
## Front matter
title: "Отчет по индивидуальному проекту"
subtitle: "Часть 5"
author: "Юсупова Ксения Равилевна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Научиться добавлять к сайту все необходимые элементы для добавления проектов и постов.

# Выполнение лабораторной работы

Для начала необходимо сделать записи для персональных проектов (рис. [-@fig:001]).

![Сделали записи для персональных проектов](image/61.png){#fig:001 width=70%}

Проверили как обновления отображаются на сайте(рис. [-@fig:002]).

![Проверили как обновления отображаются на сайте](image/62.png){#fig:002 width=70%}

Сделали пост по прошедшей неделе.(рис. [-@fig:003]).

![Сделали пост по прошедшей неделе.](image/63.png){#fig:003 width=70%}
 
Проверили как обновления отображаются на сайте(рис. [-@fig:004]).

![Проверили как обновления отображаются на сайте](image/64.png){#fig:004 width=70%}

Добавить пост на тему по выбору: Языки научного программирования..(рис. [-@fig:005]).

![Добавить пост на тему "Языки научного программирования."](image/65.png){#fig:005 width=70%}

Проверили как обновления отображаются на сайте(рис. [-@fig:006]).

![Проверили как обновления отображаются на сайте](image/66.png){#fig:006 width=70%}



# Выводы

В ходе выполнения четвертой части проекта мы научились добавлять к сайту информацию о проектах и посты.

