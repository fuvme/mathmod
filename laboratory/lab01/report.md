---
# Front matter
lang: ru-RU
title: "Отчёта по лабораторной работе"
subtitle: "Знакомство с git, создание репозитория, добавление файлов"
author: "Варвара Станиславовна Виноградова"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
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
Ознакомиться с основными функциями git, создать учетную запись, репозиторий, подпапки в нем для хранения и использования файлов. Данные навыки нужны для выполнения последущих лабораторных работ по этому предмету и другим.

# Задание

Создать учетную запись на GitHub. Создать каталог для лабораторных работ. Загрузить их в GitHub.


# Выполнение лабораторной работы

Сперва я возобновила доуступ к своей учетной записи (рис. -@fig:001)

![Мой профиль](image/screen_01.png){ #fig:001 width=70% }

Потом я скачала приложение GitHub Desktop, авторизовалась в нем по тому же логину и паролю, создала на своем компьютере папку work, в ней подпапку 2020-2021, и уже в ней создала репозиторию mathmob с помощью приложения, сделала его публичным. Далее в нем создала папку laboratory, а в нем подпапку lab_01, оставила в нем файлы и загрузила их в git, сделала commit  с помощью команды add report template (рис. -@fig:002)

![Мой репозиторий](image/screen_02.png){ #fig:002 width=70% }

Как я создавала репозиторий (рис. -@fig:003)

![Создание репозитория](image/screen_03.png){ #fig:003 width=70% }

Показываю, что файлы загрузились и видны в git (рис. -@fig:004)

![Как это выглядит на сайте](image/screen_04.png){ #fig:004 width=70% }

# Выводы

Возобновила доступ к своей учетной записи на git, вспомнила как создавать создавать репозитории, загружать файлы в GitHub.