---
## Front matter
lang: ru-RU
title: Лабораторная работа №8
author: Желдакова Виктория Алексеевна
institute: Российсикй университет дружбы народов
date: 14 мая 2022 г.

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

# Текстовый редактор vi

## Цель работы

 - Познакомиться с операционной системой Linux. 
 - Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

## Создание нового файла с использованием vi

1. Создали каталог ~/work/os/lab06, перешли в него, вызвали vi и создали новый файл hello.sh

2. Перешли в режим вставки, ввели приведённый в задании текст и перешли в командный режим, используя Esc 

3. Нажали двоеточие, ввели w и q, а затем нажали Enter 

4. Сделали файл исполняемым 

## Редактирование существующего файла

1. Вызвали vi на редактирование файла 

2. Установили курсор в конец слова HELL, в режиме вставки заменили его на HELLO.

3. В командном режиме с помощью команды dw удалили слово local.

4. Вернулись в режим вставки и написали слово LOCAL.

5. В командном режиме, с помощью Y скопировали строку echo $HELLO, а затем вставили её в конец файла, используя P 

6. Используя dd, удалили только что вставленную строку и вернули её обратно с помощью команды u 

7. Записали изменения и вышли из vi.

## Выводы 

 - Познакомились с операционной системой Linux. 
 - Получили практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.
 

