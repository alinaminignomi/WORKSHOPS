# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev] 
Отчет по лабораторной работе #1 выполнил(а):
- Юсупова Алина Руслановна
- РИ-230918
Отметка о выполнении заданий (заполняется студентом): 

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | ? |
| Задание 2 | * | ? |
| Задание 3 | * | ? |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

## Задание 1
### Написать программу Hello World на Python с запуском в Jupiter Notebook.
Ход работы:
- Скачать Anaconda и запустить Anaconda-Navigator.
- Запустить инструмент Jupyter Notebook и создать файл с именем HelloWorld.
- Открыть созданный файл с именем HelloWorld, написать в него команду print() с характерным содержанием и запустить выполнение, нажав Run.



![image](https://github.com/alinaminignomi/WORKSHOPS/blob/main/c77fdaca-36c2-4b16-9380-29d222430f49111.jpg)

## Задание 2
### Написать программу Hello World на C# с запуском на Unity.
Ход работы:
- Скачать Unity и авторизоваться.
- Скачать среду разработки для работы с C# (в моем случае Microsoft Visual Studio).
- Создать 3D проект.
- Добавить пустой GameObject.
- Написать скрипт компонента, который будет выводить в консоль "Hello World!".

```C#

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class HI : MonoBehaviour 
{
    void Start()
    {
        Debug.Log("Privet Mir!");
    }
}


```
- Повесить скрипт на объект и запустить проект.
  ![image](https://github.com/alinaminignomi/WORKSHOPS/blob/main/8d2156fe-65f8-4e7e-affe-cd0d6e8db881222.jpg)


## Задание 3
### Какую сущность(и) мы бы могли "обучить" ML-Agent-ом для того чтобы создать более качественный игровой опыт?
Сущность может выполнять задачи описанные ниже
- Советчик по предметам, сущность может анализировать инвентарь игрока и на основе этого советовать что можно заменить в определенный момент времени.
- Сущность может определять стиль игры игрока и советовать ему то с чем у него получается играть лучше всего

## Выводы

Я узнала как скачивать Anaconda и Unity, а также узнал начальные этапы использования этих ПО.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
