---
## Front matter
lang: ru-RU
title: Лабораторная работа №9
author: Желдакова Виктория Алексеевна
institute: Российский университет дружбы народов
date: 17 мая 2022 г.

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

# Текстовый редактор emacs 

## Цель работы

 - Познакомиться с операционной системой Linux. 
 - Получить практические навыки работы с редактором Emacs.

# Выполнение лабораторной работы

## Основные команды 

 - Открыли emacs и, введя комбинации C-x C-f, создали новый файл lab07.sh
 - Набрали данный нам текст
 - Сохранили файл с помощью комбинации C-x C-s
 
## Процедуры редактирования
 
 - Используя команду C-k, вырезали целую строку
 - Перенесли курсор в конец файла и, введя C-y, вставили туда вырезанную строку
 - С помощью C-space выделим фрагмент текста, скопируем его в буфер обмена на M-w и вставим в конец файла
 - Снова выделили эту область, с помощью C-w вырежем, а с помощью C-/ отменили последнее действие 
 
## Перемещение курсора 
 
Переместили курсор в начало строки, в конец, в начало буфера и в конец буфера, используя соответственно C-a, C-e, M-<, M-> 

## Управление буферами

 - Вывели список активных буферов на экран с помощью C-x C-b.
 - Переместились на новое окно, используя C-x о, и переключились на буфер scratch
 - Закрыли новое окно на C-x 0 и переключились в буфер scratch и обратно с помощью клавиш C-x b.

## Управление окнами и режим поиска

 - Поделили окно на два по вертикали с помощью C-x 3 и каждое из них на два по горизонтали с помощью C-x 2.
 - Открыли в каждом окне новый буфер и ввели несколько строк текста. 
 - Переключились в режим поиска на C-s X и попробовали найти несколько слов. 
 - Переключили результаты поиска с помощью C-s и в конце вышли из этого режима на C-g.
 - Перешли в режим поиска и замены, используя M-%, ввели текст для поиска и для замены. После подсвечивания результатов нажали !, чтобы подтвердить замену
 - Использовали другой режим поиска, введя M-s o, выделили отличие.

## Выводы

 - Познакомились с операционной системой Linux. 
 - Получили практические навыки работы с редактором Emacs.
 
