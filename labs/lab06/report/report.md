---
## Front matter
title: "Лабораторная работа номер 6"
author: "Прокопьева Марина Евгеньевна"

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

Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.

# Задание

1. Определите полное имя вашего домашнего каталога. Далее относительно этого ката-
лога будут выполняться последующие упражнения.
2. Выполните следующие действия:
2.1. Перейдите в каталог /tmp.
2.2. Выведите на экран содержимое каталога /tmp. Для этого используйте команду ls
с различными опциями. Поясните разницу в выводимой на экран информации.
2.3. Определите, есть ли в каталоге /var/spool подкаталог с именем cron?
2.4. Перейдите в Ваш домашний каталог и выведите на экран его содержимое. Опре-
делите, кто является владельцем файлов и подкаталогов?
3. Выполните следующие действия:
3.1. В домашнем каталоге создайте новый каталог с именем newdir.
3.2. В каталоге ~/newdir создайте новый каталог с именем morefun.
3.3. В домашнем каталоге создайте одной командой три новых каталога с именами
letters, memos, misk. Затем удалите эти каталоги одной командой.
3.4. Попробуйте удалить ранее созданный каталог ~/newdir командой rm. Проверьте,
был ли каталог удалён.
3.5. Удалите каталог ~/newdir/morefun из домашнего каталога. Проверьте, был ли
каталог удалён.
4. С помощью команды man определите, какую опцию команды ls нужно использо-
вать для просмотра содержимое не только указанного каталога, но и подкаталогов,
входящих в него.
5. С помощью команды man определите набор опций команды ls, позволяющий отсорти-
ровать по времени последнего изменения выводимый список содержимого каталога
с развёрнутым описанием файлов.
6. Используйте команду man для просмотра описания следующих команд: cd, pwd, mkdir,
rmdir, rm. Поясните основные опции этих команд.
7. Используя информацию, полученную при помощи команды history, выполните мо-
дификацию и исполнение нескольких команд из буфера команд.


# Выполнение лабораторной работы

Определили полное имя домашнего каталога и поперемещались между папками с помощью команд.

![](image/001.png){#fig:001 width=70%}

Выводим списки папок в нашем домашнем каталоге 

![](image/002.png){#fig:002 width=70%}

Выводим списоки папок через другую команду 

![](image/003.png){#fig:003 width=70%}

Использовать опцию /

![](image/004.png){#fig:004 width=70%}

Выводит то что нужно 

![](image/005.png){#fig:005 width=70%}

Используем команду чтобы вывели подробную информацию о каталогах 

![](image/006.png){#fig:006 width=70%}

Используем команду создани каталогов и создаем каталог newdir в домашней папке и так же создаем из домашнего каталога файл в новом каталоге 

![](image/008.png){#fig:008 width=70%}

Удаляем созданный каталог и файл в нем 

![](image/009.png){#fig:009 width=70%}

Выводим список команд и изучаем его 

![](image/010.png){#fig:010 width=70%}

Используем команду man для просмотра в диалоговом режиме

![](image/011.png){#fig:011 width=70%}

![](image/012.png){#fig:012 width=70%}

Еще один вариант с использованием man 

![](image/013.png){#fig:013 width=70%}

Используем команду для подробной информации о файлах 

![](image/014.png){#fig:014 width=70%}

Используем похожую и ищим разницу между ними 

![](image/015.png){#fig:015 width=70%}

Выводим обычный список файлов разными командами, результат тот же

![](image/016.png){#fig:016 width=70%}

Выводим историю наших команд

![](image/017.png){#fig:017 width=70%}

Выполняем команды с помощью истории 

![](image/018.png){#fig:018 width=70%}

Удаляем созданные файлы 

![](image/019.png){#fig:019 width=70%}


# Выводы

Приобрели практические навыки взаимодействия пользователя с системой посредством командной строки.


