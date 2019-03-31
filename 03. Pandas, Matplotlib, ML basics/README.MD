
# Третье занятие
Приветствуем Вас на **третьем** занятии нашего курса. Сегодня мы узнаем про классическое машинное обучение. Глубокое обучение обычно считается частью машинного обучения и по сути отличается от классических методов моделью, которая учится. Для классического машинного обучения - это решающие деревья, регрессии и т.д., а для глубокого - нейронные сети. В то же время изучить основные этапы работы с данными легче, когда моделью является решающее дерево.

В этом занятии важнее всего научиться работе с инструментами, которые помогают работать с данными - Pandas и Matplotlib.

##### При решении тетрадей Вы можете встретить функцию, которую Вы не знаете, в этом случае необходимо использовать поиск и найти информацию в документации. Почти всегда такая информация будет на первой странице поисковика. Библиотеки, которые мы используем содержат много функций, поэтому важно научиться самостоятельно пользоваться документацией.

### План занятия
#### 1.  Лекция
Данная лекция дает не только общее представление о машинном обучении, но и вводит концепции, которые будут важны в глубоком обучении, также в конце лектор рассказывает о методе ближайших соседей, на который будет домашнее задание. Эта лекция важна и ее **не стоит пропускать**. [**Запись**](https://www.youtube.com/watch?v=JSeo5mYmpuU) лекции доступна по ссылке.

Также дополнительную информацию о машинном обучении простым языком Вы можете найти в ноутбуке [**[seminar]ml_basics.ipynb**](./[seminar]ml_basics.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1d95RI9ONwSc4ObiGSDw_euH8B2QuIoxu). 

Очень важно знать основные функции потерь. Их список Вы найдете в ноутбуке [**[seminar]loss_functions.ipynb**](./[seminar]loss_functions.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1SGulXic8nNjRZZdAzBX5yUQDMwglKOWF). 

#### 2. Pandas
На семинарах мы переходим к изучению инструментов, которые являются основным фокусом данного занятия. 

**Pandas** - очень популярная библиотека для работы с табличными данными (обычно они записаны  в формате .xls или .csv). Большинство доступных данных имеют именно такой вид, поэтому она часто используется при подготовке данных. 
	
Эта библиотека очень большая и мощная, но для нашего курса будет достаточно познакомиться с основной функциональностью. [**Запись**](https://www.youtube.com/watch?v=-MZgt5pTS4g) первой части семинара даст вам достаточно умений, если Вы выполните задания в тетради [**[seminar]pandas.ipynb**](./[seminar]pandas.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1PsPo1BHd99evSphfE14FbgJWiAj5FU_k).

#### 3. Matplotlib
Продолжая изучать полезные инструменты, мы переходим к библиотеке для построения **matplotlib**. Она является самой популярной для построения графиков, несмотря на низкий уровень абстракции, который иногда заставляет программиста писать много стандартного кода (для решения этой проблемы существуют многие обертки над matplotlib, которые вы сможете потом с легкостью использовать). Далее в курсе **matplotlib** будет использоваться как для построения разнообразных графиков, так и просто для показа картинок.

Чтобы разобраться с основами вы, как всегда, можете посмотреть [**запись**](https://www.youtube.com/watch?v=-MZgt5pTS4g) нашего семинара и прорешать тетрадку, идущую к нему [**[seminar]matplotlib.ipynb**](./[seminar]matplotlib.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1R0nKyoZ3ANd4vukogEqM3egPJpvnFq41). Cdериться можно с [**[sem_solution]pandas.ipynb**](./[sem_solution]pandas.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1Y5jT0-LBISKJ1MbT_BhXjkKNaEpkgbc6)

Также есть дополнительный ноутбук о matplotlib, который рекомендуется пройти продвинутым слушателям [**extra/[extra_seminar]matplotlib.ipynb**](./extra/[extra_seminar]matplotlib.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/18eQf3-QF0p_LljHkxQfgO7Iz5YUREZHO).

##### Примечание: на семинаре были разобраны только базовые функции Pandas и matplotlib. Чтобы узнать о них больше, вы можете использовать любой хороший курс по машинному обучению. Например, запускающийся каждый сезон курс от Open Data Science. 

#### 4. Домашнее задание
Чтобы закрепить навыки, полученные на семинаре выполните задания в тетради [**[homework]pandas.ipynb**](./[homework]pandas.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1aLOZ4Uw9geV-nn2p2qEPwzDcASV43W3W). Также стоит выполнить задание на тему, объясненную на лекции - метод ближайших соседей [**[homework]knn.ipynb**](./[homework]knn.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1Zu4WVMiL-wS64c95bdQLNfcqMqFY8qSF). Если Вы участвуете в курсе, то  Вы можете проверить ответы и получить оценку, которая нужна для закрытия курса, на **canvas** нашего курса. Не слушатели, к сожалению, не имеют возможности свериться, но Вы можете присоединиться к следующей итерации курса как онлайн слушатель на нашем сайте.
