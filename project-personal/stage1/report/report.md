---
## Front matter
title: "Отчет по индивидуальному проекту"
subtitle: "Часть 1"
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

Научиться создавать сайты и размещать на Github pages заготовки для персонального сайта.

# Выполнение лабораторной работы

Для начала необходимо скачать последнюю версию Hugo для ОС Linux(рис. [-@fig:001]).

![скачали последнюю версию Hugo для ОС Linux](image/11.png){#fig:001 width=70%}

С помощью утилиты tar распакуем архив с Hugo (рис. [-@fig:002]).

![распакуем архив с Hugo](image/12.png){#fig:002 width=70%}

Установим Hugo, переместив исполняемый файл в директорию /usr/local/bin (рис. [-@fig:003]).

![Установим Hugo](image/13.png){#fig:003 width=70%}
 
Зайдём на страницу шаблона и создадим из неё репозиторий github. Назовём наш репозиторий blog. (рис. [-@fig:004]).

![репозиторий blog](image/14.png){#fig:004 width=70%}

Клонируем созданный репозиторий к себе на компьютер(рис. [-@fig:005]).

[Клонируем созданный репозиторий](image/15.png){#fig:005 width=70%}

Запустим Hugo. В момент запуска он подготовит папку с сайтом, создав дополнительные каталоги (рис. [-@fig:006]).

![Запустим Hugo](image/16.png){#fig:006 width=70%}

Запустим Hugo с опцией server, которая позволит нам запустить наш сайт(рис. [-@fig:007]).

![Запустим Hugo с опцией server](image/17.png){#fig:007 width=70%}

Перейдя по адресу localhost:1313, мы увидим наш сайт (рис. [-@fig:008]).

![полученный сайт](image/18.png){#fig:008 width=70%}

Теперь создадим второй репозиторий, на котором будет висеть наш сайт. Его нужно назвать в формате "Имя аккаунта на гитхаб + .github.io" (рис. [-@fig:009]).

![создадим второй репозиторий](image/19.png){#fig:009 width=70%}

Обновляем репозиторий, делая коммит и выкладывая изменения на гитхаб (рис. [-@fig:010]).

![Обновляем репозиторий](image/110.png){#fig:010 width=70%}

Теперь добавим второй репозиторий как сабмодуль первого(рис. [-@fig:011]).

![добавим второй репозиторий как сабмодуль первого](image/111.png){#fig:011 width=70%}

Выгрузим изменения на гитхаб(рис. [-@fig:012]).

![Выгрузим изменения на гитхаб](image/112.png){#fig:012 width=70%}

Теперь посмотрим, как выглядит наш сайт, (рис. [-@fig:013]).

![Просматриваем полученный сайт](image/113.png){#fig:013 width=70%}

# Выводы

В ходе лабораторной работы мы научились создавать сайты и размещать на Github pages заготовки для персонального сайта.

