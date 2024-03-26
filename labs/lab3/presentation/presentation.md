---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №3.
subtitle: Основы информационной безопасности.
author:
  - Рогожина Н.А.
institute:
  - Российский университет дружбы народов, Москва, Россия

date: 16 марта 2024

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
  * Студентка 2го курса, НКАбд-02-22
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

## Создание нового пользователя

![Добавление нового пользователя](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab3/report/image/1.png){#fig:001 width=70%}

## Сравнение домашних директорий

![guest2:pwd](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab3/report/image/4.png){#fig:004 width=70%}

## id VS groups

![groups|id](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab3/report/image/10.png){#fig:010 width=70%}

## id VS groups

![id](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab3/report/image/11.png){#fig:011 width=70%}

## Изменение прав доступа директории

![chmod 000](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab3/report/image/15.png){#fig:015 width=70%}

## Права доступа

![d-----x---](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab3/report/image/18.png){#fig:018 width=70%}

## Права доступа

![d---r-----](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab3/report/image/20.png){#fig:020 width=70%}

## Права доступа

![d----w----](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab3/report/image/22.png){#fig:022 width=70%}

## Права доступа

![d---rw----](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab3/report/image/26.png){#fig:026 width=70%}

## Права доступа

![d---r-x---](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab3/report/image/24.png){#fig:024 width=70%}

## Права доступа

![d----wx---](/home/narogozhina/work/study/2023-2024/Информационная безопасность/infosec/labs/lab3/report/image/28.png){#fig:028 width=70%}

