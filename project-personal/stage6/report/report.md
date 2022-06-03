---
## Front matter
title: "Отчёт по индивидуальному проекту"
subtitle: "Шестой этап"
author: "Желдакова Виктория Алексеевна"

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

 - Сделать поддержку английского и русского языков.
 - Разместить элементы сайта на обоих языках.
 - Разместить контент на обоих языках.
 - Сделать пост по прошедшей неделе.
 - Добавить пост на тему по выбору (на двух языках).

# Выполнение лабораторной работы

Для того чтобы добавить поддержку русского языка на сайте перешли в каталог content/config/_default и изменили файл languages.yaml (рис. [-@fig:001])

![Добавление поддержки русского языка](image/1.png){ #fig:001 width=70% }

Всё содержимое папки content добавили в её подкаталог en, скопировали в подкаталог ru и перевели все ранее добавленные элементы на русский (рис. [-@fig:002] и рис. [-@fig:003])

![Перевод ранее добавленных элементов сайта](image/2.png){ #fig:002 width=70% }

![Результат добавления всех ранее созданных элементов на русский язык](image/3.png){ #fig:003 width=70% }

Создали пост на тему по выбору и о прошедшей неделе на двух языках (рис. [-@fig:004], рис. [-@fig:005] и рис. [-@fig:006])

![Создание поста на тему по выбору на английском](image/4.png){ #fig:004 width=70% }

![Результат добавления постов на русском](image/5.png){ #fig:005 width=70% }

![Результат добавления постов на английском](image/6.png){ #fig:006 width=70% }

# Выводы

 - Сделали поддержку английского и русского языков.
 - Разместили элементы сайта на обоих языках.
 - Разместили контент на обоих языках.
 - Сделали пост по прошедшей неделе.
 - Добавили пост на тему по выбору (на двух языках).

::: {#refs}
:::
