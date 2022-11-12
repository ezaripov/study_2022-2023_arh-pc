---
## Front matter
title: "Лабораторная работа №5"
author: "Зарипов Евгений Сергеевич"

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

Освоение процедуры компиляции и сборки программ, написанных на ассемблере NASM

# Выполнение лабораторной работы

![Создаем необходимый файл](./image/ris1.png)

![Перепишем представленный в лабораторной работе код на зыке "насм" в открывшийся файл](./image/ris2.png)

![Протранслируем файл hello.nasm](./image/ris3.png)

![Тут мы получаем объектный файл и файл "листинга", компилируем исполняемый файл](./image/ris4.png)

![Создаем исполняемый файл из объектного](./image/ris5.png)

![Запускаем исполняемый файл](./image/ris6.png)

#Самостоятельная работа

![Копируем файл hello.asm, как lab05.asm и открываем его](./image/ris7/png)

![Редактируем открытый файл lab05.asm](./image/ris8.png)

![Создаем объектный файл и "листинг". Компилируем его под именем lab05, после чего запускаем. После запуска получаем необходимый результат.](./image/ris9.png)

# Выводы

Я получил навыки компиляции и сборки программ, написанных на ассемблере NASM

