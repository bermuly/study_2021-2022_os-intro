---
## Front matter
lang: ru-RU
title: Лабораторная работа №13
author: Желдакова Виктория Алексеевна
institute: Российский университет дружбы народов
date: 3 июня 2022 г.

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

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Средства, применяемые при разработке программного обеспечения в ОС типа UNIX/Linux

## Цель работы

Приобрести простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

## Выполнение лабораторной работы

 - В домашнем каталоге создали подкаталог ~/work/os/lab_prog и в нём файлы calculate.h, calculate.c, main.c 
 - Выполнили компиляцию программы посредством gcc 
 - Создали Makefile 
 - Запустили GDB, загрузив в него программу для отладки и для запуска программы внутри отладчика использовали команду run 
 - Для постраничного вывода кода использовали команду list, затем просмотрели строки с 12 по 15
 
## Выполнение лабораторной работы
 
 - Просмотрели содержимое файла calculate.c, используя команду list с параметрами и установили  точку останова на 21 строке 
 - Вывели информацию о всех точках останова
 - Запустили программу и убедились, что программа останавливается в момент прохождения точки останова
 - Использовали команду Backtrace для вывода всего стека вызываемых функций
 - Вывели значение переменной Numeral с помощью команд print и display
 - Удалили точку останова и вывели информацию о имеющихся точках останова
 - С помощью утилиты splint проанализировали коды файлов calculate.c и main.c.

## Вывод

Приобрели простейшие навыки разработки, анализа, тестирования и отладки приложений в ОС типа UNIX/Linux на примере создания на языке программирования С калькулятора с простейшими функциями.

