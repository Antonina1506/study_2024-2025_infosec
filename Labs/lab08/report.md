---
## Front matter
title: "Отчёт по лабораторной работе №8"
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

Освоить на практике применение режима однократного гаммирования
на примере кодирования различных исходных текстов одним ключом.


# Выполнение лабораторной работы

1) Функция для генерации ключа.
(рис. [-@fig:001])

![Генерация ключа](1.JPG){#fig:001 width=70%}

2) Функция для (де)шифрования.
(рис. [-@fig:002])

![Шифрование](2.JPG){#fig:002 width=70%}

3) Код для вывода результатов и результаты.
рис. [-@fig:003]) - (рис. [-@fig:004])

![Подбор ключа](3.JPG){#fig:003 width=70%}

![Результаты](4.JPG){#fig:004 width=70%}

4) Код для расшифровки фразы с помощью второй фразы и результаты.
(рис. [-@fig:005]) - (рис. [-@fig:006])

![Код расшифровки](5.JPG){#fig:005 width=70%}

![Результаты расшифровки](6.JPG){#fig:006 width=70%}

5) Листинг программы.
(рис. [-@fig:007])

![Листинг программы](7.JPG){#fig:007 width=50%}

# Вывод

В результате выполнения работы мы научились на практике применять режим однократного гаммирования на примере кодирования различных исходных текстов одним ключом.


# Список литературы{.unnumbered}
1) https://esystem.rudn.ru/pluginfile.php/2357159/mod_resource/content/2/008-lab_crypto-key.pdf