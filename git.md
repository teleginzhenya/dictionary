# Словарь терминов Git и GitHub

Оглавление: A [B](#b) [C](#c) D E [F](#f) [G](#g) H I J K L [M](#m) N [O](#o) [P](#p) Q [R](#r) S T [U](#u) V W X Y Z

## B

### branch

**ветка,** параллельная версия репозитория. Она включена в этот репозиторий, но не влияет на другие версии, тем самым позволяя разработчикам независимо работать с кодом одного проекта. Когда вы внесли нужные изменения, вы можете объединить (см. [мёрж](#merge)) их с главной версией (см. [мастер](#master)).

## C

### clone

**клонирование,** копирование репозитория с удалённого сервера на локальный компьютер для дальнейшей работы.

### code review

**ревью кода,** процесс проверки кода на соответствие требованиям, задачам и внешнему виду.

### commit

**коммит,** фиксация изменений и запись их в репозиторий.

## F

### fork

**форк,** копия репозитория. Его также можно рассматривать как внешнюю [ветку](#branch) для текущего репозитория. Копию публичного репозитория на Гитхабе может сделать любой пользователь, после чего он может прислать изменения (см. [коммит](#commit)) через [пулреквест](#pull-request).

## G

### git

**гит,** система контроля и управления версиями файлов.

### GitHub

**Гитхаб,** веб-сервис для размещения репозиториев и совместной разработки проектов.

## M

### master

**мастер,** главная или основная [ветка](#branch) репозитория.

### merge

**мёрж,** слияние изменений из одной ветки в другую ветку того же репозитория.

## O

### origin

**ориджин,** короткое название ссылки на [удалённый репозиторий](#repository).

## P

### pull

**пул,** получение последних изменений из [удалённого репозитория](#repository).

### pull request

**пулреквест,** запрос на слияние форка (см. [форк-репозиторий](#repository)) с основным репозиторием (см. [мастер-репозиторий](#repository)). Пулреквест может быть принят или отклонён владельцем репозитория.

### push

**пуш,** отправка всех неотправленных коммитов на [удалённый репозиторий](#repository).

## R

### repository

**репозиторий,** папка, в которой находятся: конфиги, журналы операций, индекс файлов и сами файлы репозитория.

**локальный репозиторий,** репозиторий на локальном компьютере разработчика, где происходит разработка и фиксируются изменения, которые отправляются на удалённый репозиторий.

**удалённый репозиторий,** копия репозитория, хранящаяся отдельно от локального (обычно на удалённом сервере, например [Гитхаб](#GitHub)). Чаще всего используется группой разработчиков для синхронизации всех изменений в проекте.

**мастер-репозиторий,** главный репозиторий, от него начинаются [форки](#fork).

**форк-репозиторий,** [форк](#fork) мастер-репозитория.

## U

### upstream

**апстрим,** короткое название ссылки на [мастер-репозиторий](#repository).