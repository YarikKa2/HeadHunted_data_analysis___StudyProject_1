# Анализ базы данных с платформы HeadHunter, 
Анализ базы данных выгруженных с сайта поиска вакансий hh.ru.  <br>
В проекты был произведен базовый анализ структуры данных, преобразование данных, <br>
разведывательный анализ и очистка данных.

## Содержание
- [Технологии](#технологии)
- [Использование](#Использование)
- [ВАЖНО](#ВАЖНО)
- [Команда проекта](#команда-проекта)
- [Дополнительно](#Дополнительно)

## Технологии
- [Visual Studio Code](https://code.visualstudio.com/)
- [Python 3.9.10](https://www.python.org/downloads/release/python-3910/)

## Использование
Для работы данной программы потребуется импортировать несколько библиотек <br>
numpy ``` import numpy as np ``` <br>
pandas ``` import pandas as pd ``` <br>
plotly.express ``` import plotly.express as px ``` <br>
<br>
Если у вас отсутвует какой либо из вышеперечисленных пакетов, установите его. <br>
В терминале введите ``` pip install 'название_пакета_без_кавычек' ```<br>

Для работы plotly требуется <ins>**nbformat**</ins> (версия 4.2.0 или выше), а также kaleido для сохранения изображений в png <br>
Для установки nbformat введите в терминале ``` pip install nbformat ``` <br>
Для установки kaleido введите в терминале ``` pip install -U kaleido ``` <br>
Обязательно перезагрузите kernel после установки (либо перезагрузите Visual Studio Code)

## ВАЖНО
В репозитории присутствуют необходимые CSV-файлы, добавленные с помощью Git LFS (Large file storage), однако могут возникнуть проблемы с их скачиванием.  <br>
Если возникли проблемы, данные можно скачать с гугл-диска по ссылке: https://drive.google.com/drive/folders/1om_3DkIHgHaCUyF35hZJAn0Zq8owqGiF?dmr=1&ec=wgc-drive-hero-goto

https://drive.google.com/file/d/1JQ8BWBP4bsjMV9hVeKBoVQ8r1OwmCBKL/view?usp=sharing

## Команда проекта

- [Капущак Ярослав]

## Дополнительно
Может помочь в случае возникновения проблем с nbformat: <br> (https://stackoverflow.com/questions/66557543/valueerror-mime-type-rendering-requires-nbformat-4-2-0-but-it-is-not-installed)
