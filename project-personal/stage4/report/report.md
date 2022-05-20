---
## Front matter
title: "Индивидуальный проект"
subtitle: "Четвёртый этап"
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

 - Добавить к сайту ссылки на научные и библиометрические ресурсы.
 - Сделать пост по прошедшей неделе.
 - Добавить пост на тему по выбору: Создание презентации.

# Выполнение лабораторной работы

Для того, чтобы добавить ссылки на научные и библиометрические ресурсы, мы перешли в каталог /content/authors/admin/ и изменили файл index.md (рис. [-@fig:001] и рис. [-@fig:002]).

![Добавление ссылок на научные и библиометрические ресурсы](image/1.png){ #fig:001 width=70% }

![Результат добавления ссылок на ресурсы](image/2.png){ #fig:002 width=70% }

Используя команду hugo new post создали файлы для нового поста по прошедшей неделе и для поста по выбранной теме. Оформили посты и сохранили (рис. [-@fig:003], рис. [-@fig:004] и рис. [-@fig:005]).

![Создание поста по прошедшей неделе](image/3.png){ #fig:003 width=70% }

![Создание поста по теме "Как создавать эффективные презентации"](image/4.png){ #fig:004 width=70% }

![Результат добавления постов на сайт](image/5.png){ #fig:005 width=70% }

# Выводы

 - Добавили к сайту ссылки на научные и библиометрические ресурсы.
 - Сделали пост по прошедшей неделе.
 - Добавили пост на тему по выбору: Создание презентации.

::: {#refs}
:::
