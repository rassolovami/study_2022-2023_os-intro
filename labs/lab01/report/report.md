---
## Front matter
title: "Лабораторная работа №1"
author: "Рассолова Маргарита Сергеевна"

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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.


# Теоретическое введение

Linux - семейство ОС, работающих на основе одноименного ядра. 
Fedora - образ мощной и минимальной базовой ОС (дистрибутив Linux).

# Выполнение лабораторной работы

1. Переключилась на роль супер-пользователя. (рис. @fig:001).

![Супер-пользователь](Снимок экрана от 2023-02-22 21-12-38.jpg){#fig:001 width=70%}

2. Обновила все пакеты. (рис. @fig:002).

![Обновление пакетов](Снимок экрана от 2023-02-22 21-21-26.jpg){#fig:002 width=70%}

3. Ввела команду программы для удобства работы в консоли. (рис. @fig:003).

![Программа для удобства работы в консоли](Снимок экрана от 2023-02-22 22-08-44.jpg){#fig:003 width=70%}

4. Установила программное обеспечение. (рис. @fig:004).

![Установка ПО](Снимок экрана от 2023-02-22 22-10-12.jpg){#fig:004 width=70%}

5. Отключила SELinux. (рис. @fig:005).

![Отключение SELinux](Снимок экрана от 2023-02-22 22-15-39.jpg){#fig:005 width=70%}

6. Установила драйвера, предварительно перейдя в терминальной мультиплексор и переключившись на роль супер-пользователя. (рис. @fig:006).

![Установка драйверов](Снимок экрана от 2023-02-22 22-25-25.jpg){#fig:006 width=70%}

7. Установила pandoc. (рис. @fig:007).

![Установка pandoc](Снимок экрана от 2023-02-22 22-32-38.jpg){#fig:007 width=70%}

8. Установила расширения к нему. (рис. @fig:008).

![Установка расширений](Снимок экрана от 2023-02-22 22-44-12.jpg){#fig:008 width=70%}

9. Установила texlive. (рис. @fig:009).

![Установка texlive](Снимок экрана от 2023-02-22 22-44-40.jpg){#fig:009 width=70%}


# Самостоятельная работа

1. Получила информацию, заданную к самостоятельной работе. (рис. @fig:010, рис. @fig:011, рис. @fig:012, рис. @fig:013).

![Анализ последовательности загрузки системы](Снимок экрана от 2023-02-23 20-17-42.jpg){#fig:010 width=70%}
![Версия ядра, частота процессора, модель процессора](Снимок экрана от 2023-02-23 20-19-38.jpg){#fig:011 width=70%}
![Объем доступной оперативной памяти](Снимок экрана от 2023-02-23 20-19-51.jpg){#fig:012 width=70%}
![Тип файловой системы корневого каталога](Снимок экрана от 2023-02-23 20-20-43.jpg){#fig:013 width=70%}

# Выводы

Приобрела практические навыки установки операционной системы на виртуальную машину, настроила минимально необходимые для дальнейшей работы сервисы.

# Контрольные вопросы

1. Имя пользователя, идентификационный номер пользователя, идентификационный номер группы, пароль, полное имя, домашний каталог, начальную оболочку.

2. man, cd, ls, du, mkdir.

3. Файловая система - архитектура хранения битов на жестком диске\организация каталог в соответствии с идеалогией Unix.

4. Команда "findmnt".


# Список литературы{.unnumbered}

::: {#refs}
:::
