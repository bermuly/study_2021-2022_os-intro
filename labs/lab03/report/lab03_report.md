---
## Front matter
title: "Отчёт по лабораторной №3"
subtitle: "Markdown"
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

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

- Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.

- В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md (в архиве,
поскольку он должен содержать скриншоты, Makefile и т.д.).

# Теоретическое введение

Markdown — облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций.

# Выполнение лабораторной работ

Перед началом выполнения лабораторной работы мы скачали pandoc, pandoc-crossref и pandoc-citeproc.

Для подготовки отчёта мы используем заранее подготовленный шаблон для данной лабораторной работы. Начинаем переносить основные пункты лабораторной №2 в Markdown файл (рис. [-@fig:001]).

![Оформление пунктов "Цель работы", "Задание" и "Теоретическое введение" в Markdown](lab03_image/1.png){ #fig:001 width=70% }

Вставку изображений и ссылки на изображения оформляем по приведённому шаблону (рис. [-@fig:002]).

![Пример оформления вставки изображений и ссылок на изображения](lab03_image/2.png){ #fig:002 width=70% }

Полностью переносим данные в Markdown и переходим к конвертированию в другие форматы (рис. [-@fig:003]).

![Команды для конвертирования markdown файла в docx и pdf с помощью pandoc](lab03_image/3.png){ #fig:003 width=70% }

Проверяем корректность конвертирования файлов (рис. [-@fig:004]).

![Полученный в результате конвертации pdf файл](lab03_image/4.png){ #fig:004 width=70% }

# Выводы

Научились оформлять отчёты с помощью легковесного языка разметки Markdown и конвертировать их в форматы docx и pdf.

