---
## Front matter
title: "Лабораторная работа №7"
subtitle: "Архитектура компьютера"
author: "Зарипов Евгений Сргеевич"

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

Освоение арифметических инструкций языка ассемблера NASM

# Выполнение лабораторной работы


![создаем необходимый файл lab7-1.asm](./image/1.jpg)

![Результат работы листинг 7.1](./image/2.jpg)

![Результат работы листинга после замены строк](./image/4.png)

![Cоздаем файл lab7-1.asm](./image/5.png)

![Результат работы листинг 7.2](./image/3.jpg)

![выполнениt арифметических операций в NASM на примере программы, вычисляющей арифметическое выражение 𝑓(𝑥) = (5 ∗ 2 +3)/3 и 𝑓(𝑥) = (4 ∗ 6 + 2)/5](./image/7.png)

#ВЫполнение самостоятельной работы:

![Определяемся с номером варианта](./image/8.png)

![Пишем программу для вычисления знаечения 𝑥3/2 + 1 при х1=2 и х2=5](./image/11.png)
![](./image/12.png)
![](./image/13.png)

![Проверяем работу подставляя необходимые значения (2 и 5, это последние два ввода)](./image/9.png)

#Вопросы:

![1. mov eax,msg call sprintLF]
![2. Для ввода значения переменной Х с клавиатуры]
![3. Для преоьразования кода переменной из таблицы "Аски" в число]
![4. mov ebx, div ebx inc edx]
![5. ebx]
![6. ДЛя увелечения значения edx на 1]
![mov eax, edx call iprintLF]

# Выводы

Я освоил арифметические инструкции языка ассемблера NASM

# Список литературы{.unnumbered}

::: {#refs}
:::
