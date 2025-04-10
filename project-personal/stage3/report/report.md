---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Часть 3"
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

Добавить к своему сайту достижения.

# Выполнение лабораторной работы

Добавим информацию о навыках (Skills)(рис. [-@fig:001]).

![информация о навыках](image/61.png){#fig:001 width=70%}

Смотрим как информация о навыках отображается на сайте(рис. [-@fig:002]).

![проверили skills на сайте](image/62.png){#fig:002 width=70%}

Добавим информацию об опыте (Experience)(рис. [-@fig:003]).

![информация об опыте](image/63.png){#fig:003 width=70%}

Добавим информацию о достижениях (Accomplishments).(рис. [-@fig:004]).

![информация о достижениях (Accomplishments)](image/64.png){#fig:004 width=70%}

Смотрим как информация о достижениях (Accomplishments) отображается на сайте(рис. [-@fig:005]).

![проверили Accomplishments на сайте](image/65.png){#fig:005 width=70%}

Сделаем пост по прошедшей неделе(рис. [-@fig:006]).

![пост по прошедшей неделе](image/66.png){#fig:006 width=70%}

Проверили, что пост по прошедшей неделе был успешно выгружен (рис. [-@fig:007]).

![проверили состояние первого поста](image/67.png){#fig:007 width=70%}

Добавить пост на тему по выбору, была выбрана тема "Языки разметки. LaTeX" (рис. [-@fig:008]).

![написали пост на тему "Языки разметки. LaTeX"](image/68.png){#fig:008 width=70%}

Проверили, что пост на тему по выбору "Языки разметки. LaTeX" успешно выгружен (рис. [-@fig:009]).

![проверили состояние второго поста](image/69.png){#fig:009 width=70%}

# Выводы

В ходе лабораторной работы были добавлены достижения к моему сайту 

