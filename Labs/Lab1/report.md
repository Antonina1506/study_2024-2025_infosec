---
## Front matter
title: "Отчёт по лабораторной работе №10"
author: "Паращенко Антонина Дмитриевна"

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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Ход лабораторной работы
## Задание 1

Создаём каталог с именем пользователя, создаём виртуаьлную машину и выставляем нужные настройки.  (рис. [-@fig:001]) - (рис. [-@fig:007])

![](screen.jpg){ #fig:001 width=70% }

![](screen1.jpg){ #fig:002 width=70% }

![](screen2.jpg){ #fig:003 width=70% }

![](screen3.jpg){ #fig:004 width=70% }

![](screen4.jpg){ #fig:005 width=70% }

![](screen01.jpg){ #fig:006 width=70% }

![](screen02.jpg){ #fig:007 width=70% }

## Задание 2

Запускаем виртуальную машину и настраеваем её, ждём установки (рис. [-@fig:008]) - (рис. [-@fig:013])

![](screen08.jpg){ #fig:008 width=70% }

![](screen03.jpg){ #fig:009 width=70% }

![](screen04.jpg){ #fig:010 width=70% }

![](screen05.jpg){ #fig:011 width=70% }

![](screen07.jpg){ #fig:012 width=70% }

![](screen10.jpg){ #fig:013 width=70% }

## Задание 3

Перезапускаем машину, создаём пользователя (рис. [-@fig:014]) - (рис. [-@fig:015])

![](screen11.jpg){ #fig:014 width=70% }

![](screen12.jpg){ #fig:015 width=70% }

## Задание 4

Переименуем хост (рис. [-@fig:016])

![](screen13.jpg){ #fig:016 width=70% }

## Домашнее задание

Получить информацию с помощью команды dmesg | grep -i "то, что ищем" (рис. [-@fig:017])

![](screen13.jpg){ #fig:017 width=70% }


# Вывод
Создала виртуальную машину и установила и настроила операционную систему Linux. 

