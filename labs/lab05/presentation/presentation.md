---
## Front matter
lang: ru-RU
title: Лабораторная работа №5
author: Желдакова Виктория Алексеевна
institute: Российский университет дружбы народов
date: 4 мая 2022 г.

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

# Анализ файловой системы Linux. Команды для работы с файлами и каталогами

## Цель работы

Ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.

## Ход работы

Первым делом выполнили все примеры, приведённые в первой части описания лабораторной работы.

Затем мы скопировали файл /usr/include/sys/io.h в домашний каталог и назвали его equipment. В домашнем каталоге создали директорию ~/ski.plases. Переместили файл equipment в каталог ~/ski.plases. Переименовали файл ~/ski.plases/equipment в ~/ski.plases/equiplist.

## Ход работы

Создали в домашнем каталоге файл abc1 и скопировали его в каталог ~/ski.plases и назвали equiplist2. Создали каталог с именем equipment в каталоге ~/ski.plases. Переместили файлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment.

Создали и переместили каталог ~/newdir в каталог ~/ski.plases и назвали его plans

## Ход работы

Создали два каталога (australia, play) и два файла (my_os, feathers). Изменили их права доступа на следующие: (drwxr--r--) australia, (drwx--x--x) play, (-r-xr--r--) my_os, (-rw-rw-r--) feathers.

Просмотрели содержимое файла /etc/passwd с помощью команды cat.

## Ход работы

Скопировали файл ~/feathers в файл ~/file.old, переместили его в каталог play. Скопировали этот каталог в каталог fun. Переместили его в каталог ~/play и назвали games. Лишили владельца файла ~/feathers права на чтение. Попытались просмотреть файл и скопирвать его в другой, но получили ошибку "отказано в доступе". Вернули владельцу право на чтение.

Проверили права доступа к каталогу play и лишили владельца права на выполнение. Попробовали перейти в каталог play, но получили ошибку "отказано в доступе". Вернули права на выполнение. 

Прочитали manual по командам mount, fsck, mkfs, kill и кратко их охарактеризовали.

## Выводы

Ознакомились с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобрели практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.





