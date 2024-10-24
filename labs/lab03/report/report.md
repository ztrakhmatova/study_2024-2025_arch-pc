---
## Front matter
title: "Отчёта по лабораторной работе №3"
subtitle: "Дисциплина: архитектура компьютера"
author: "Рахматова Жылдыз Талантбековна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.


# Задание

1. Выполнить лабораторную работу №3 
2. Выполнить задание для самостоятельной работы


# Теоретическое введение

Markdown - легковесный язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций. Внутритекстовые формулы делаются аналогично формулам LaTeX. В Markdown вставить изображение в документ можно с помощью непосредственного указания адреса изображения. Синтаксис Markdown для встроенной ссылки состоит из части [link text], представляющей текст гиперссылки, и части (file-name.md) – URL-адреса или имени файла, на который дается ссылка. Markdown поддерживает как встраивание фрагментов кода в предложение, так и их размещение между предложениями в виде отдельных огражденных блоков. Огражденные блоки кода — это простой способ выделить синтаксис для фрагментов кода.


# Выполнение лабораторной работы

 Для выполнения лабораторной работы №3 нужно открыть терминал
 
 Далее нужно перейти в каталог курса сформированный при выполнении лабораторной работы №2   (рис. [-@fig:001]).

![переход в каталог курса](image/1.jpg){#fig:001 width=70%}

 Обновляем локальный репозиторий, скачав изменения из удаленного репозитория с помо-
щью команды git pull (рис. [-@fig:002]).

![команда git pull](image/2.jpg){#fig:002 width=70%}

 Перейдем в каталог с шаблоном отчета по лабораторной работе №3 (рис. [-@fig:003])

![переход в каталог с шаблоном отчета](image/3.jpg){#fig:003 width=70%}

Проведем компиляцию шаблона с использованием Makefile. Для этого нужно ввести ко-
манду make (рис. [-@fig:004])

![команда make](image/4.jpg){#fig:004 width=70%}

Далее удаляем полученные файлы с помощью команды make clean (рис. [-@fig:005])

![команда make clean](image/5.jpg){#fig:005 width=70%}

Открываем файл report.md с помощью текстового редактора gedit raport.md  (рис. [-@fig:006])

![файл report.md](image/6.jpg){#fig:006 width=70%}

# Выводы

В результате выполнения данной лабораторной работы я освоила процедуры оформления отчетов с помощью легковесного языка разметки Markdown.


