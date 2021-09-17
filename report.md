---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №1"
subtitle: "Развертывание виртуальной машины"
author: "Казарина Полина Аркадьевна НБИбд-01-18"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of pictures
fontsize: 14pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Times
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
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

# Цель работы

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, размещение файлов на сервисе Git и подготовка отчета в формате Markdown.

# Выполнение лабораторной работы

Создаю виртуальную машину

![Создание новой виртуальной машины](image/1.png){ #pic:001 width=70% }

Задаю конфигурацию жёсткого диска — VDI, динамический виртуальный диск.

![Конфигурация жёсткого диска](image/2.png){ #pic:002 width=70% }

![Конфигурация жёсткого диска](image/3.png){ #pic:003 width=70% }

![Конфигурация жёсткого диска](image/4.png){ #pic:004 width=70% }

![Конфигурация жёсткого диска](image/5.png){ #pic:005 width=70% }

![Конфигурация жёсткого диска](image/6.png){ #pic:006 width=70% }

Добавляю новый привод оптических дисков и выбираю образ 

![Конфигурация системы](image/8.png){ #pic:008 width=70% }

Запускаю виртуальную машину и выбираю установку системы на жёсткий диск.
Устанавливаю язык для интерфейса и раскладки клавиатуры

![Установка языка](image/9.png){ #pic:009 width=70% }

Указываю параметры установки

![Установка разбиения диска](image/11.png){ #pic:011 width=70% }

![Установка имени хоста](image/12.png){ #pic:012 width=70% }

![Установка часового пояса](image/10.png){ #pic:010 width=70% }

Создаю пароль суперпользователя

![Установка пароля root](image/13.png){ #pic:013 width=70% }
 
Перехожу к этапу установки и дожидаюсь его завершения.

![Создание пользователя](image/14.png){ #pic:014 width=70% }

# Вывод

Мы приобрели практические навыки установки операционной системы на виртуальную машину, Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, разместили файлы работы на сервисе Git и подготовили отчет в формате Markdown.