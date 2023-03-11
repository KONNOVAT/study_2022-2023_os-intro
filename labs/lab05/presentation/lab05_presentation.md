---
## Front matter
lang: ru-RU
title: Лабораторная работа №5.
author: |
	Коннова Татьяна Алексеевна
institute: |
	RUDN, Москва, Россия
date: 2023, 11 марта

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Анализ файловой системы Linux. Команды для работы с файлами и каталогами.

## Копирование файла и изменение его названия

1. cp - команда для копирования файлов или каталогов.
2. ls - команда для просмотра содержимого каталогов.

![Копирование файла io.h под названием equipment. Проверка.](image/1.png){ #fig:001 width=70% }

## Создание директории

mkdir - команда для создания директорий.

![Создание директории ski.plases](image/2.png){ #fig:002 width=100% }

## Перемещение файла

mv - команда для перемещения или изменения названия файлов или каталогов.

![Перемещение файла equipment в каталог ski.plases](image/3.png){ #fig:003 width=100% }

## Изменение названия файла

![Переименование файла equipment в equiplist](image/4.png){ #fig:004 width=100% }

## Создание, копирование и изменение названия файла

touch - команда для создания файлов.

![Создание файла abc1 и копирование его в каталог ski.plases под названием equiplist2](image/5.png){ #fig:005 width=100% }

## Создание каталога

![Создание каталога equipment в каталоге ski.plases](image/6.png){ #fig:006 width=100% }

## Перемещение файлов в подкаталог

![Перемещение файлов в подкаталог equipment](image/7.png){ #fig:007 width=100% }

## Создание, копирование и изменение названия каталога
	
![Создание каталога newdir и перемещение его в каталог ski.plases под названием plans](image/8.png){ #fig:008 width=100% }

## Создание 2 каталогов и 2 файлов

![Создание каталогов и файлов](image/9.png){ #fig:009 width=100% }

## Присвоение определённых прав доступа

Присвоим каждому из каталогов и файлов определённые права доступа. 

![Присваивание прав доступа](image/10.png){ #fig:010 width=70% }

## Просмотр содержимого файла

cat - команда для просмотра содержимого файла. 

![Просмотр содержимого файла passwd](image/11.png){ #fig:011 width=70% }

## Копирование файла

![Копирование файла feathers в file.old](image/12.png){ #fig:012 width=100% }

## Перемещение файла

![Перемещение файла file.old в каталог play](image/13.png){ #fig:013 width=100% }

## Копирование каталога

![Копирование каталога play в каталог fun](image/14.png){ #fig:014 width=100% }

## Перемещение и изменение названия каталога

![Перемещение каталога fun с изменением название на games](image/15.png){ #fig:015 width=100% }

## Работа с правами файла

chmod u-r - команда для лишения владельца файла права на чтение.

chmod u+r - команда для присвоения владельцу файла права на чтение.

![Лишение права на чтение. Попытки чтения и копирования файла. Возвращение права на чтение](image/16.png){ #fig:016 width=100% }

## Работа с правами каталога

chmod u-x - команда для лишения владельца каталога права на выполнение.

chmod u+x - команда для присвоения владельцу каталога права на выполнение.

![Лишение права на выполнение. Попытка перехода в каталог. Возвращение права на выполнение](image/17.png){ #fig:017 width=100% }

# Прочитаем с помощью команды man следующие команды: mount, fsck, mkfs, kill. Кратко охарактеризуем эти команды.

## mount

Для просмотра используемых в операционной системе файловых систем используется команда mount.

![man mount](image/18.png){ #fig:018 width=60% }

## fsck

С помощью команды fsck можно проверить (а в ряде случаев восстановить) целостность файловой системы.

![man fsck](image/19.png){ #fig:019 width=70% }

## mkfs

mkfs используется для создания файловой системы Linux на некотором устройстве, обычно в разделе жёсткого диска. В качестве аргумента filesys для файловой системы может выступать или название устройства (например, /dev/hda1, /dev/sdb2) или точка монтирования (например, /, /usr, /home).

![man mkfs](image/20.png){ #fig:020 width=60% }

## kill

Утилита kill отправляет сигнал процессу(-ам), указанному с помощью каждого из операндов идентификатор_процесса. По умолчанию утилита kill отправляет сигнал SIGTERM, но эту настройку по умолчанию можно переопределить путем определения имени сигнала для отправки.

![man kill](image/21.png){ #fig:021 width=60% }

# Выводы

В ходе выполнения лабораторной работы мы ознакомились с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобрели практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.


## {.standout}

Спасибо за внимание!