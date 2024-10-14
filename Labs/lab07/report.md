---
## Front matter
title: "Отчёт по лабораторной работе №7"
subtitle: "Дисциплина: Основы информационной безопасности"
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

Освоить на практике применение режима однократного гаммирования.


# Выполнение лабораторной работы

1) Функция для генерации ключа.
(рис. [-@fig:001])

![Генерация ключа](2.JPG){#fig:001 width=70%}

2) Функция для (де)шифрования.
(рис. [-@fig:002])

![Шифрование](3.JPG){#fig:002 width=70%}

3) Функция для подбора ключа.
рис. [-@fig:003])

![Подбор ключа](4.JPG){#fig:003 width=70%}

4) Код для вывода результатов и результаты.
(рис. [-@fig:004])

![Результаты](5.JPG){#fig:004 width=70%}

5) Листинг программы.
(рис. [-@fig:005])

![Листинг](1.JPG){#fig:005 width=70%}


# Вывод

В результате выполнения работы мы научились на практике применять режим однократного гаммирования.


# Список литературы{.unnumbered}
1) https://esystem.rudn.ru/pluginfile.php/2357157/mod_resource/content/2/007-lab_crypto-gamma.pdf