---
# Front matter
lang: ru-RU
title: "Презентация по лабораторной работе №2"
subtitle: "Дискреционное разграничение прав в CentOS"
author: "Оразклычев Довлет НФИбд-02-18"

# Formatting
toc-title: "Содержание"
toc: false # Table of contents
toc_depth: 2
lof: false # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: Arial
romanfont: Arial
sansfont: Arial
monofont: Arial
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цели и задачи работы

## Цель лабораторной работы

Получить практические навыки работы в консоли с атрибутами файлов, закрепить теоретические основы дискреционного разграничения доступа в современных системах с открытым кодом на базе CentOS.

# Процесс выполнения лабораторной работы

## Лабораторная работа 2

![Создание пользователя guest](image/1.jpg){ #fig:001 width=70% }

\pagebreak

## Лабораторная работа 2

![Переход на пользователя guest](image/2.jpg){ #fig:002 width=70% }

\pagebreak

## Лабораторная работа 2

![Команды: pwd, whoami, id, groups](image/3.jpg){ #fig:003 width=70% }

\pagebreak

## Лабораторная работа 2

![Команда cat /etc/passwd с фильтром и без](image/4.jpg){ #fig:004 width=70% }

\pagebreak

## Лабораторная работа 2

![Правильность выполнения команды](image/5.jpg){ #fig:005 width=70% }

\pagebreak

## Лабораторная работа 2

![Попытка создать файл в директории](image/6.jpg){ #fig:006 width=70% }

\pagebreak

# Выводы по проделанной работе

## Вывод

В ходе выполнения лабораторной работы были получены навыки работы с атрибутами файлов и сведения о разграничении доступа.