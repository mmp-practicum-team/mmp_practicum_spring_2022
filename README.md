# Курс "Практикум на ЭВМ 2021/2022" для бакалавров 3 курса кафедры ММП ВМК МГУ, весенний семестр

Этот репозиторий содержит материалы к курсу "Практикум на ЭВМ", читаемому бакалаврам 3 курса кафедры ММП факультета ВМК МГУ в весеннем семестре 2022 года.

## О курсе

* Обязательный курс для студентов каф. ММП 3 курса, 6 семестр
* Отчётность: зачёт с оценкой

Курс читается в поддержку курсов "Глубинное обучение" и "Математические методы распознавания образов" (машинное обучение, часть 2), читаемых на кафедре ММП. В ходе курса студенты выполняют различные практические задания.

[Курс лекций по глубинному обучению](https://github.com/Dyakonov/DL)


[Общефакультетский курс лекций по машинному обучению](https://github.com/MSU-ML-COURSE/ML-COURSE-21-22)

[Курс лекций по машинному обучению](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%82%D0%B5%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5_%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D1%8B_%D1%80%D0%B0%D1%81%D0%BF%D0%BE%D0%B7%D0%BD%D0%B0%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%92.%D0%92.%D0%9A%D0%B8%D1%82%D0%BE%D0%B2%29)

[Курс семинаров по машинному обучению](https://github.com/mmp-mmro-team/mmp_mmro_spring_2021)

## Материалы

Видеозаписи практикумов [выкладываются в этом плейлисте](https://youtube.com/playlist?list=PLVF5PzSHILHQVzBxACB3-UQr8BmhoDEIn).
Видеозаписи практикумов прошлого года [в этом плейлисте](https://www.youtube.com/playlist?list=PLVF5PzSHILHRH_HD4SzuaAz05eByyqYMl).

Задания [выкладываются здесь](https://github.com/mmp-practicum-team/mmp_practicum_spring_2022/tree/main/Tasks).


## Занятия

| Дата | Номер | Тема | Материалы | ДЗ |
| :---: | :---: | --- | --- | --- |
| 09 февраля  | 1  | <ul><li>Введение в нейросети</li><li>MLP</li><li>Инициализация сетей</li></ul> | [Введение в нейросети. MLP. Инициализация сетей](Seminars/Seminar%2001/Введение%20в%20нейросети.%20MLP.%20Инициализация%20сетей.ipynb) | ¯\\\_(ツ)\_/¯ |
| 16 февраля  | 2  | <ul><li>Автоматическое дифференцирование</li><li>Задачи</li><li>Backpropagation</li></ul> | [Решение задач](Seminars/Seminar%2002/tasks.pdf) | [Полносвязная нейронная сеть на numpy](Tasks/task1/lab_01.ipynb) |
| 02 марта  | 3  | <ul><li>Dropout</li><li>BatchNorm</li><li>Введение в PyTorch</li></ul> |  [PyTorch](Seminars/Seminar%2003)  | ¯\\\_(ツ)\_/¯ |
| 09 марта  | 4  | <ul><li>Свёртки</li><li>Свёрточные сети в Pytorch</li><li>Сегментация</li></ul> |  [Свёртки. Свёрточные сети в Pytorch. Сегментация](Seminars/Seminar%2004)  | ¯\\\_(ツ)\_/¯ |
| 16 марта  | 5  | <ul><li>Свёрточные сети в Pytorch</li><li>Сегментация</li></ul> |  [FCN](Seminars/Seminar%2005)  | [Сегментация изображений](Tasks/task2/lab_02.ipynb) |


## Формат сдачи курса

* В рамках семестра предполагается выполнить **четыре больших практических заданий** стоимостью 10 баллов каждое и **одно практическое задание** стоимостью 5 баллов.
* За каждый день просрочки задания назначается штраф — 1 балл.
* B<sub>fall</sub> — баллы за осенний семестр, B<sub>fall,max</sub> = 230 — максимальное число баллов за осенний семестр.
* B<sub>spring</sub> — баллы за весенний семестр, B<sub>spring,max</sub> = 45 — максимальное число баллов за весенний семестр.
* B = 3<sup>B<sub>fall</sub></sup>&frasl;<sub>B<sub>fall,max</sub></sub> + 7<sup>B<sub>spring</sub></sup>&frasl;<sub>B<sub>spring,max</sub></sub> — баллы за годовой курс.
    * B ≥ 8 и 5 практических заданий сданы на оценку ≥ 4 ⇒ отлично
    * B ≥ 6 и 4 практических задания сданы на оценку ≥ 4 ⇒ хорошо
    * B ≥ 4 и 3 практических задания сданы на оценку ≥ 4 ⇒ удовлетворительно
    * иначе ⇒ неудовлетворительно
​
* При определении числа зачтённых заданий рассматриваются только задания весеннего семестра. Штраф за просрочку при этом не учитывается.
