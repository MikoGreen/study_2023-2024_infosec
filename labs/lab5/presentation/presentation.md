---
## Front matter
lang: ru-RU
title: Презентация по лабораторной работе №5.
subtitle: Основы информационной безопасности.
author:
  - Рогожина Н.А.
institute:
  - Российский университет дружбы народов, Москва, Россия

date: 13 апреля 2024

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

### Объект и предмет исследования

- Права доступа к каталогам и файлам

## Цели и задачи

Изучение механизмов изменения идентификаторов, применения SetUID- и Sticky-битов. Получение практических навыков работы в консоли с дополнительными атрибутами. Рассмотрение работы механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.

# Выполнение лабораторной работы

## 

![Вход в систему](image/1.png){#fig:001 width=70%}

## 

![Вход в систему](image/2.png){#fig:002 width=70%}

## 

![simpleid.c](image/3.png){#fig:003 width=70%}

## 

![компиляция](image/4.png){#fig:004 width=70%}

## 

![проверка работоспособности](image/5.png){#fig:005 width=70%}

## 

![id](image/6.png){#fig:006 width=70%}

## 

![simpleid2.c](image/7.png){#fig:007 width=70%}

## 

![simpleid2](image/8.png){#fig:008 width=70%}

## 

![смена прав от root](image/9.png){#fig:009 width=70%}

## 

![проверка](image/10.png){#fig:010 width=70%}

## 

![id VS simpleid2](image/11.png){#fig:011 width=70%}

## 

![SetGID-бит](image/12.png){#fig:012 width=70%}

## 

![readfile](image/13.png){#fig:013 width=70%}

## 

![компиляция и проверка прав](image/14.png){#fig:014 width=70%}

## 

![Смена владельца и прав](image/15.png){#fig:015 width=70%}

## 

![попытка №1](image/16.png){#fig:016 width=70%}

## 

![SetUID](image/17.png){#fig:017 width=70%}

## 

![смена владельца и прав](image/18.png){#fig:018 width=70%}

## 

![попытка №2](image/19.png){#fig:019 width=70%}

## 

![/tmp](image/20.png){#fig:020 width=70%}

## 

![file01.txt](image/21.png){#fig:021 width=70%}

## 

![guest2](image/22.png){#fig:022 width=70%}

## 

![попытка №3](image/23.png){#fig:023 width=70%}

## 

![попытка №4](image/24.png){#fig:024 width=70%}

## 

![попытка №5](image/25.png){#fig:025 width=70%}

## 

![смена прав /tmp](image/26.png){#fig:026 width=70%}

## 

![](image/27.png){#fig:027 width=70%}

## 

![повтор](image/28.png){#fig:028 width=70%}

## 

![возвращение прав](image/29.png){#fig:029 width=70%}

