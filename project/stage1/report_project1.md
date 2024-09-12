---
## Front matter
title: "Отчёт по индивидуальному проекту, этап №1"
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

Установить дистрибутив Kali Linux в виртуальную машину.

# Ход лабораторной работы

## Создание виртуальной машины

#### №1 

Устанавливаем виртуальную машину по инструкции, как в лабораторной работе №1.

(рис. [-@fig:001]) - (рис. [-@fig:004])

![Установка виртуальной машины](1.JPG) {#fig:001 width=70% }

![Жесткий диск](2.JPG){ #fig:002 width=70% }

![Виртуальный жесткий диск](3.JPG){ #fig:003 width=70% }

![Параметры машины](4.JPG){ #fig:004 width=70% }

#### №2 

Подключаем образ Kali Linux.

(рис. [-@fig:005])

![Образ диска](5.JPG){ #fig:005 width=70% }

#### №3

Устанавливаем Kali Linux.

(рис. [-@fig:006])

![Установка Kali Linux](6.JPG){ #fig:006 width=70% }

#### №4

Настройки установки.

(рис. [-@fig:007]) - (рис. [-@fig:023])

![Язык](7.JPG){ #fig:007 width=70% }

![Загрузка компонентов](8.JPG){ #fig:008 width=70% }

![Настройка сети](9.JPG){ #fig:009 width=70% }

![Настройка сети, домен](10.JPG){ #fig:010 width=70% }

![Учётная запись](11.JPG){ #fig:011 width=70% }

![Учётная запись](12.JPG){ #fig:012 width=70% }

![Время](13.JPG){ #fig:013 width=70% }

![Диск](14.JPG){ #fig:014 width=70% }

![Диск](15.JPG){ #fig:015 width=70% }

![Диск](16.JPG){ #fig:016 width=70% }

![Диск](17.JPG){ #fig:017 width=70% }

![Установка](18.JPG){ #fig:018 width=70% }

![Программное обеспечение](19.JPG){ #fig:019 width=70% }

![Настройка менеджера дисплеев](20.JPG){ #fig:020 width=70% }

![Установка системного загрузчика](21.JPG){ #fig:021 width=70% }

![Установки](22.JPG){ #fig:022 width=70% }

![Завершение установки](23.JPG){ #fig:023 width=70% }

#### №5 

Вход в учётную запись.

(рис. [-@fig:024]) - (рис. [-@fig:025])

![Пользователь](24.JPG){ #fig:024 width=70% }

![Установка гостевых дополнений](25.JPG){ #fig:025 width=70% }

#### №6 

Перезагружаем виртуальную машину.

(рис. [-@fig:026])

![Рабочий стол](26.JPG){ #fig:026 width=70% }

# Вывод
Установили виртуальную машину с дистрибутивом Kali Linux.

# Литература
1. Парасрам, Ш. Kali Linux: Тестирование на проникновение и безопасность : Для профессионалов. Kali Linux / Ш. Парасрам, А. Замм, Т. Хериянто, и др. – Санкт-Петербург : Питер, 2022. – 448 сс.
– Санкт-Петербург : Питер, 2022. – 448 сс.
