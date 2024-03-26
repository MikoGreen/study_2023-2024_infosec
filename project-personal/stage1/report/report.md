---
## Front matter
title: "Отчёт по индивидуальному проекту. Этап 1."
subtitle: "Основы информационной безопасности"
author: "Рогожина Надежда Александровна, НКАбд-02-22"

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

# Цель проекта

Целью проекта ставится приобретение теоретических и практических навыков и обучение способам тестирования веб приложений.

# Задание

- Найти максимальное количество уязвимостей различных типов.
- Реализовать успешную эксплуатацию каждой уязвимости.

# Теоретическое введение

Ищутся уязвимости в специально предназначенном для этого веб приложении под названием Damn Vulnerable Web Application (DVWA). Назначение DVWA — попрактиковаться в некоторых самых распространённых веб уязвимостях. В данном этапе задача - установить *Kali Linux* на Virtual Box. *Kali Linux* представляет собой стратегически продуманную операционную систему, предлагающую множество передовых инструментов сетевым аналитикам и тестерам на проникновение. Kali содержит сканеры, снифферы и многие другие инструменты для атак. ОС может обеспечить полный сеанс пентеста или более конкретные атаки.

# Выполнение индивидуального проекта

В первую очередь, откроем окно Virtual Box и добавим новую машину (рис. [-@fig:001]):

![Добавление](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/1.jpg){#fig:001 width=70%}

Так как я скачивала образ **специально подготовленный для VirtualBox**, то после распаковки скачанного архива выбираем образ диска (рис. [-@fig:002]):

![Выбор образа диска](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/2.jpg){#fig:002 width=70%}

После выбора диска, машина уже установлена с необходимыми характеристиками (на основе Linux Debian) (рис. [-@fig:003]):

![Машина и характеристики](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/3.jpg){#fig:003 width=70%}

После этого попробуем запустить виртуальную машину (рис. [-@fig:004]):

![Первый запуск](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/4.jpg){#fig:004 width=70%}

Вводим имя пользователя и пароль (рис. [-@fig:005]):

![user+passwd](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/5.jpg){#fig:005 width=70%}

Таким образом, машина установлена (рис. [-@fig:006]):

![Успешный запуск](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/6.jpg){#fig:006 width=70%}

# Выводы

В ходе первого этапа индивидуального проекта *Kali Linux* была успешно установлена.

# Список литературы{.unnumbered}

::: {#refs}
:::
