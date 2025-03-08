---
## Front matter
title: "Лабораторная работа № 4"
subtitle: "Продвинутое использование git"
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

Получение навыков правильной работы с репозиториями git.


# Выполнение лабораторной работы

## Установка git-flow

Установка из коллекции репозиториев Copr(рис. [-@fig:001]).

![Установка git-flow](image/41.png){#fig:001 width=70%}

## Настройка Node.js

Установили Node.js. Для работы с Node.js добавим каталог с исполняемыми файлами, устанавливаемыми yarn, в переменную PATH.

Запукаем и перелогинимся:(рис. [-@fig:002]).

![Установка и настройка Node.js](image/42.png){#fig:002 width=70%}

## Общепринятые коммиты

commitizen. Данная программа используется для помощи в форматировании коммитов.       standard-changelog. Данная программа используется для помощи в создании логов.(рис. [-@fig:003]).

![commitizen и standard-changelog](image/43.png){#fig:003 width=70%}

## Создание репозитория git

Подключение репозитория к github. Создайте репозиторий на GitHub. Для примера назовём его git-extended. Делаем первый коммит и выкладываем на github (рис. [-@fig:004]).

![Делаем первый коммит и выкладываем на github](image/44.png){#fig:004 width=70%}

Конфигурация общепринятых коммитов(рис. [-@fig:005]).

![Конфигурация для пакетов Node.js](image/45.png){#fig:005 width=70%}

Необходимо заполнить несколько параметров пакета: Название пакета, лицензия пакета, список лицензий для npm. Предлагается выбирать лицензию CC-BY-4.0. Таким образом, файл package.json приобретает вид:(рис. [-@fig:006]).

![Измененный файл package.json](image/46.png){#fig:006 width=70%}

Добавим новые файлы, выполним коммит и отправим на github(рис. [-@fig:007]).

![Добавим новые файлы, выполним коммит и отправим на github](image/47.png){#fig:007 width=70%}

# Выводы

В ходе выполнения лабораторной работы были получены навыки правильной работы с репозиториями git.

