---
## Front matter
title: "Лабораторная работа 2"
subtitle: "Язык разметки Markdown"
author: "Ошкодер С.А."

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

1. Цель работы

2. Задание

3. Теоретическое введение

4. Выполнение Лабораторной работы

5. Вывод

# Цель работы

Изучить идеологию и применение средств контроля версий.
Приобрести практические навыки по работе с системой «git».

# Задание

1. Ознакомиться с документацией к лабораторной работе;
2. Настроить Github;
3. Создать SSH-ключ и рабочее пространство;
4. Создать репозиторий и настроить каталог курса;
5. Копировать, перемещать, переименовывать файлы;
6. Выполнить ряд заданий для самостоятельной работы;

# Теоретическое введение

Здесь описываются теоретические аспекты, связанные с выполнением работы.

Например, в табл. [-@tbl:std-dir] приведено краткое описание стандартных каталогов Unix.

: Описание некоторых каталогов файловой системы GNU Linux {#tbl:std-dir}

| Имя каталога | Описание каталога                                                                                                          |
|--------------|----------------------------------------------------------------------------------------------------------------------------|
| `/`          | Корневая директория, содержащая всю файловую                                                                               |
| `/bin `      | Основные системные утилиты, необходимые как в однопользовательском режиме, так и при обычной работе всем пользователям     |
| `/etc`       | Общесистемные конфигурационные файлы и файлы конфигурации установленных программ                                           |
| `/home`      | Содержит домашние директории пользователей, которые, в свою очередь, содержат персональные настройки и данные пользователя |
| `/media`     | Точки монтирования для сменных носителей                                                                                   |
| `/root`      | Домашняя директория пользователя  `root`                                                                                   |
| `/tmp`       | Временные файлы                                                                                                            |
| `/usr`       | Вторичная иерархия для данных пользователя                                                                                 |

Более подробно про Unix см. в [@tanenbaum_book_modern-os_ru; @robbins_book_bash_en; @zarrelli_book_mastering-bash_en; @newham_book_learning-bash_en].

# Выполнение лабораторной работы

В пункте 2.4.2 требуется задать предварительную конфигурацию git. См. рис1
![drg](image/1.png){#fig:001 width=70%}

Рис1

В пунктах 2.4.3-2.4.4 требуется создать SSH ключ и рабочее пространство. См. Рис 2
![drg](image/2.png){#fig:001 width=70%}

Рис2

В пунктах 2.4.5-2.4.6 требуется создать репозиторий курса и настроить каталог курса. См. рис.3-6
![drg](image/3.png){#fig:001 width=70%}

Рис3

![drg](image/4.png){#fig:001 width=70%}

Рис4

![drg](image/5.png){#fig:001 width=70%}

Рис5

![drg](image/6.png){#fig:001 width=70%}

Рис6

В пункте 2.5 требуется выполнить ряд заданий для самостоятельного решения. См. рис. 7-8

![drg](image/7.png){#fig:001 width=70%}

Рис7

![drg](image/8.png){#fig:001 width=70%}

Рис8

# Выводы

В процессе выполнения лабораторной работы, я ознакомился с git,
изучил ряд команд и подготовил рабочее пространство для
дальнейших работ.

# Список литературы{.unnumbered}

::: {#refs}
:::
