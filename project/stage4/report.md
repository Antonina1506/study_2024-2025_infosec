---
## Front matter
title: "Отчёт по индивидуальному проекту этап №4"
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

Изучить работу базового сканера безопасности веб-сервера ***nikto***. Просканировать уязвимости в веб-приложении DVWA. 

# Выполнение лабораторной работы

1)Подготавливаем приложение DVWA для сканирования.
 (рис. [-@fig:001])
 
![Запуск apache2](1.JPG){#fig:001 width=70%}

2)  Заходим на сайт DVWA и и меняем уровень безопасности на минимальный.
(рис. [-@fig:002])

![Безопасность low](2.JPG){#fig:002 width=70%}

3)  Запускаем сканер *nikto*.
(рис. [-@fig:003])

![Запуск nikto](3.JPG){#fig:003 width=70%}

4) Сканируем веб-приложение по полному адресу.
(рис. [-@fig:004])

![Сканирование по URL](4.JPG){#fig:004 width=70%}

5) Сканируем веб-приложение по адресу хоста и адресу порта.
(рис. [-@fig:005])

![Сканирование по хосту и порту](5.JPG){#fig:005 width=70%}


# Вывод

В результате выполнения работы мы познакомились с работой базового сканера безопасности веб-сервера ***nikto***, а также просканировали уязвимости в веб-приложении DVWA. 

# Список литературы{.unnumbered}
1) Парасрам, Ш. Kali Linux: Тестирование на проникновение и безопасность : Для профессионалов. Kali Linux / Ш. Парасрам, А. Замм, Т. Хериянто, и др. – Санкт-Петербург : Питер, 2022. – 448 сс.