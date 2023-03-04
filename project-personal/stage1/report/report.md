---
## Front matter
title: "Персональный проект"
subtitle: "Этап 1"
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
biblatex: false
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

Целью данной работы является размещение на Github pages заготовки для персонального сайта.


# Выполнение лабораторной работы

1. Скачала архив hugo с Гитхаба. Распаковала его. (рис. @fig:001).

![Файлы](image/Снимок экрана от 2023-02-25 18-41-02.png){#fig:001 width=70%}

2. Вырезала файл hugo и перенесла его в созданную папку bin. (рис. @fig:002).

![Перенос файла](image/Снимок экрана от 2023-02-25 18-42-06.png){#fig:002 width=70%}

3. Создала новый репозиторий. (рис. @fig:003).

![Создание репозитория](image/Снимок экрана от 2023-02-25 18-47-21.png){#fig:003 width=70%}

4. Клонировала репозиторий. (рис. @fig:004).

![Клонирование репозитория](image/Снимок экрана от 2023-02-25 18-49-33.png){#fig:004 width=70%}

5. Выполнила команду "~/bin/hugo". (рис. @fig:005).

![Выполнение команды](image/Снимок экрана от 2023-02-25 20-16-56.png){#fig:005 width=70%}

6. Удалила файл "public". (рис. @fig:006).

![Удаление файла](image/Снимок экрана от 2023-02-25 20-17-35.png){#fig:006 width=70%}

7. Выполнила команду "~/bin/hugo server". Я вручную скопировала ссылку. (рис. @fig:007).

![Продолжение выполнения команды](image/Снимок экрана от 2023-02-25 20-18-52.png){#fig:007 width=70%}

8. В браузере ввела скопированную из терминала ссылку. (рис. @fig:008).

![Переход по ссылке](image/Снимок экрана от 2023-02-25 20-26-29.png){#fig:008 width=70%}

9. Создала собственный репозиторий. (рис. @fig:009).

![Создание собственного репозитория](image/Снимок экрана от 2023-02-25 20-31-29.png){#fig:009 width=70%}

10. Клонировала его. (рис. @fig:010).

![Клонирование собственного репозитория](image/Снимок экрана от 2023-02-25 20-33-06.png){#fig:010 width=70%}

11. Просмотрела содержимое и переключилась на новую ветку. (рис. @fig:011).

![Переключение на ветку](image/Снимок экрана от 2023-02-25 20-34-46.png){#fig:011 width=70%}

12. Создала пустой файл и отправила на Гит. (рис. @fig:012).

![Создание пустого файла и его отправка на Гит](image/Снимок экрана от 2023-02-25 20-36-50.png){#fig:012 width=70%}

13. Проверила его наличие на Гите. (рис. @fig:013).

![Проверка](image/Снимок экрана от 2023-02-25 20-37-37.png){#fig:013 width=70%}

14. Команда игнорирования файлов. (рис. @fig:014).

![Команды](image/Снимок экрана от 2023-02-25 20-42-45.png){#fig:014 width=70%}

15. Закомментировала файл "public". (рис. @fig:015).

![Комментирование](image/Снимок экрана от 2023-02-25 20-41-28.png){#fig:015 width=70%}

16. Повторила команду с hugo. (рис. @fig:016).

![Повторение](image/Снимок экрана от 2023-02-25 20-44-25.png){#fig:016 width=70%}

17. Отредактировала репозиторий. (рис. @fig:017).

![Редактирование](image/Снимок экрана от 2023-02-25 20-45-42.png){#fig:017 width=70%}

18. Добавила на сайт. (рис. @fig:018).

![Добавление на сайт](image/Снимок экрана от 2023-02-25 20-46-48.png){#fig:018 width=70%}

19. Закончила отправку на Гит. (рис. @fig:019).

![Завершение отправки](image/Снимок экрана от 2023-02-25 20-47-31.png){#fig:019 width=70%}

20. Проверила наличие файлов на Гите. (рис. @fig:020).

![Завершение отправки](image/Снимок экрана от 2023-02-25 20-48-11.png){#fig:020 width=70%}

# Выводы

Завершила первый этап выполнения работы с персональным проектом.


