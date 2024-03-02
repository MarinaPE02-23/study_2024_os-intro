---
## Front matter
title: "Индивидуальный проект"
subtitle: "Первый этап"
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

Размещение на Github pages заготовки для персонального сайта.

# Задание

Установить необходимое программное обеспечение.
Скачать шаблон темы сайта.
Разместить его на хостинге git.
Установить параметр для URLs сайта.
Разместить заготовку сайта на Github pages.

# Выполнение индивидуального проекта

1. Скачивание файла hugo-extended

![hugo](image/001.png){#fig:001 width=70%}

![hugo](image/002.png){#fig:002 width=70%}

![hugo](image/003.png){#fig:003 width=70%}

2. Создание репозитория project по шаблону и клонирование

![project](image/004.png){#fig:004 width=70%}

![project](image/005.png){#fig:005 width=70%}

![project](image/006.png){#fig:006 width=70%}

3. Скачивание модулей hugo 

![hugo](image/008.png){#fig:008 width=70%}

![hugo](image/009.png){#fig:009 width=70%}


4.  Удаление ненужных файлов 

![project](image/025.png){#fig:025 width=70%}

![project](image/026.png){#fig:026 width=70%}

![project](image/027.png){#fig:027 width=70%}

5. Подключение к серверу 

![hugo](image/010.png){#fig:010 width=70%}

![hugo](image/011.png){#fig:011 width=70%}

![hugo](image/028.png){#fig:028 width=70%}

![hugo](image/031.png){#fig:031 width=70%}

6. Создание нового репозитория MarinaPE02-23

![](image/029.png){#fig:0029 width=70%} 

![](image/012.png){#fig:012 width=70%}

7. Клонирование 

![](image/033.png){#fig:033 width=70%}

![](image/034.png){#fig:034 width=70%}

8. Добавление файлов в репозиторий 

![](image/017.png){#fig:017 width=70%}

9. Изменение файла .gitignore и дальнейшие этапы 
 
![](image/036.png){#fig:036 width=70%}

10. Заходим на наш сайт 

![](image/019.png){#fig:019 width=70%}

# Выводы

Разместили на Github pages заготовки для персонального сайта.
