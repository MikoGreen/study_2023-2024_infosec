---
## Front matter
lang: ru-RU
title: Индивидуальный проект. Этап 1.
subtitle: Установка Kali Linux
author:
  - Рогожина Н.А.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 02 марта 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Рогожина Надежда Александровна
  * Студентка 1го курса, НКАбд-02-22
  * Компьютерные и информационные науки
  * Российский университет дружбы народов
  * [Github](https://github.com/MikoGreen/study_2023-2024_infosec)

:::
::: {.column width="30%"}

:::
::::::::::::::

# Вводная часть

## Актуальность

Ищутся уязвимости в специально предназначенном для этого веб приложении под названием Damn Vulnerable Web Application (DVWA). Назначение DVWA — попрактиковаться в некоторых самых распространённых веб уязвимостях. В данном этапе задача - установить *Kali Linux* на Virtual Box. *Kali Linux* представляет собой стратегически продуманную операционную систему, предлагающую множество передовых инструментов сетевым аналитикам и тестерам на проникновение. Kali содержит сканеры, снифферы и многие другие инструменты для атак. ОС может обеспечить полный сеанс пентеста или более конкретные атаки.

## Объект и предмет исследования

- Kali Linux
- VirtualBox

## Цели и задачи

Целью проекта ставится приобретение теоретических и практических навыков и обучение способам тестирования веб приложений.

- Найти максимальное количество уязвимостей различных типов.
- Реализовать успешную эксплуатацию каждой уязвимости.

# Выполнение

## Процесс установки

В первую очередь, откроем окно Virtual Box и добавим новую машину:

![Добавление](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/1.jpg){#fig:001 width=70%}

## Процесс установки

Так как я скачивала образ **специально подготовленный для VirtualBox**, то после распаковки скачанного архива выбираем образ диска:

![Выбор образа диска](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/2.jpg){#fig:002 width=70%}

## Процесс установки

После выбора диска, машина уже установлена с необходимыми характеристиками (на основе Linux Debian):

![Машина и характеристики](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/3.jpg){#fig:003 width=70%}

## Первый запуск

После этого попробуем запустить виртуальную машину:

![Первый запуск](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/4.jpg){#fig:004 width=70%}

## Первый запуск

Вводим имя пользователя и пароль:

![user+passwd](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/5.jpg){#fig:005 width=70%}

## Первый запуск

Таким образом, машина установлена:

![Успешный запуск](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/project-personal/stage1/report/image/6.jpg){#fig:006 width=70%}

# Выводы

## Выводы

В ходе первого этапа индивидуального проекта *Kali Linux* была успешно установлена.

