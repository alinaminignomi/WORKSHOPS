# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #5 выполнил(а):
- Юсупова Алина Руслановна
- РИ-230918
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | * |
| Задание 2 | * | * |
| Задание 3 | * | * |

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
Познакомиться с одной из первых моделей нейросетей - перцептроном и реализовать эту модель в Unity
## Задание 1. Найдите внутри C# скрипта “коэффициент корреляции” и сделать выводы о том, как он влияет на обучение модели
Ход работы:
- Внутри скрипта есть поле forceMultiplier — это поправочный коэффициент силы, который нужен для того, чтобы сила не была слишком маленькой, находясь в диапазоне от -1 до 1.

## Задание 2. Изменить параметры файла yaml-агента и определить какие параметры и как влияют на обучение модели. Привести описание не менее трех параметров.
Ход работы:
- max_steps: Данный параметр указывает на максимальное количество итераций; чем больше значение, тем эффективнее будет обучение модели.
- trainer_type: Этот параметр отвечает за выбор алгоритма для интеллектуального обучения.
- num_layers: Этот параметр определяет число слоев в вашей обучающей сети. Увеличение этого значения делает модель более глубокой.
  
## Задание 3. Приведите примеры, для каких игровых задачи и ситуаций могут использоваться примеры 1 и 2 с ML-Agent’ом. В каких случаях проще использовать ML-агент, а не писать программную реализацию решения?
Ход работы:
- Если модель научится ориентироваться на цель, одна из моделей может использоваться, например, для преследования игрока. Кроме того, она может управлять направлением различных снарядов (таких как пули или фаерболы) в сторону цели.
- Вторая модель можно представить в виде курьера, перемещающегося между двумя точками.
- ML-агента удобно применять, когда задача имеет множество способов решения или не имеет четко определенного алгоритма. Это касается ситуаций с множеством возможных исходов. Также, если алгоритм крайне сложный и его реализация вручную требует значительных затрат ресурсов и времени, это тоже является хорошим примером для использования ML-агентов.

## 1 Поиск агентом объекта на сцене

![image](https://github.com/alinaminignomi/WORKSHOPS/blob/main/W5z1.jpg)
1 модель

![image](https://github.com/alinaminignomi/WORKSHOPS/blob/main/W5z2.jpg)
3 модели

![image](https://github.com/alinaminignomi/WORKSHOPS/blob/main/W5z3.jpg)
9 моделей

![image](https://github.com/alinaminignomi/WORKSHOPS/blob/main/W5z4.jpg)
27 моделей


Хотя модель иногда выдает непредсказуемые результаты после обучения, в общем, процесс обучения был успешным, и она справляется с поставленной задачей. Это свидетельствует о том, что есть потенциал для дальнейшего улучшения и оптимизации ее работы.

## 2 Симулятор добычи ресурсов
После сделанных пунктов по методичке объект "перетаскивал" ресурсы

![image](https://github.com/alinaminignomi/WORKSHOPS/blob/main/W5z3.jpg)
Когда сцена была запущена, все объекты перемещали ресурсы с высокой точностью. Это, вероятно, связано с тем, что я использовала проект с уже обученной моделью. Такой подход позволил достичь хороших результатов с минимальными усилиями. 




## Выводы
Я изучила систему ML-агента в юнити, научился обучать готовые модели и тестировать их
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