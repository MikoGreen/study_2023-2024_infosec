---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №2.
subtitle: Основы информационной безопасности.
author:
  - Рогожина Н.А.
institute:
  - Российский университет дружбы народов, Москва, Россия

date: 01 марта 2024

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

- Умение работать в консоли с атрибутами файлов, а также знание основ разграничения доступа в современных системах с открытым кодом на базе OC Linux значительно улучшит и упростит понимание и работу с безопасностью данных.

## Объект и предмет исследования

- Права доступа к каталогам и файлам

## Цели и задачи

- Научиться работать с правами доступа через консоль
- Понимать разницу между доступом владельца, группы, всех пользователей

# Содержание лабораторной работы

## Создание нового пользователя

![Добавление нового пользователя](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/1.png){#fig:001 width=70%}

## Сравнение домашних директорий

![guest:pwd](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/3.png){#fig:003 width=70%}

## Сравнение домашних директорий

![narogozhina:pwd](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/4.png){#fig:004 width=70%}

## id VS groups

![guest:id+groups](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/7.png){#fig:007 width=70%}

## Сравнение доступа к директориям

![guest:ls -l /home](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/11.png){#fig:011 width=70%}

## Сравнение доступа к директориям

![narogozhina:ls -l /home](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/12.png){#fig:012 width=70%}

## Просмотр атрибутов

![guest:lsattr /home](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/13.png){#fig:013 width=70%}

## Просмотр атрибутов

![narogozhina:lsattr /home](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/14.png){#fig:014 width=70%}

## Создание каталога и его атрибутов

![Создание каталога dir1, его атрибуты](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/15.png){#fig:015 width=70%}

## Попытка создать файл

![Попытка создать файл](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/16.png){#fig:016 width=70%}

## Проверка

![Проверка командой](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/17.png){#fig:017 width=70%}

## Права доступа

![d--x------](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/18.png){#fig:018 width=70%}

## Права доступа

![dr--------](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/19.png){#fig:019 width=70%}

## Права доступа

![d-w-------](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/20.png){#fig:020 width=70%}

## Права доступа

![drw-------](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/21.png){#fig:021 width=70%}

## Права доступа

![dr-x------](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/22.png){#fig:022 width=70%}

## Права доступа

![d-wx------](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab2/report/image/23.png){#fig:023 width=70%}

# Выводы

## Выводы

В ходе выполнения работы мы получили практические навыки работы в консоли с атрибутами файлов и закрепили теоретические основы разграничения доступа в современных системах с открытым кодом на базе OC Linux.
