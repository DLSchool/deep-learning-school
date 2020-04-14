
# 3. Introduction to Machine Learning

Приветствуем вас на **третьем** занятии нашего курса. Сегодня мы узнаем про **классическое машинное обучение**. Глубокое обучение обычно считается **частью** машинного обучения и по сути отличается от классических методов лишь устройством  обучаемой модели. Для классического машинного обучения - это **решающие деревья, линейная регрессия и т.д.**, а для глубокого - **нейронные сети**. В то же время изучить основные этапы работы с данными легче, когда моделью является решающее дерево.

<p align=center>
  <img src="https://sun9-3.userapi.com/c830508/v830508404/1c016d/QaHblsjxJ7k.jpg" width=600>
</p>

Нв этом занятии важнее всего научиться работе с инструментами, которые помогают работать с данными - Pandas и Matplotlib.
При решении тетрадей Вы можете встретить какие-либо функции языка Python, которые не видели раньше. В этом случае необходимо **использовать поиск** или **найти информацию в документации**. Почти всегда такая информация будет на первой странице поисковика. Библиотеки, которые мы используем, содержат много функций, поэтому важно научиться **самостоятельно** пользоваться документацией.

### Лекция: Основы машинного обучения

Лекция дает не только общее представление о машинном обучении, но и вводит концепции, которые будут важны в глубоком обучении. Также в конце лектор рассказывает о методе ближайших соседей, по которому будет домашнее задание. Эта лекция важна и ее **не стоит пропускать**. [**Запись лекции**](https://www.youtube.com/watch?v=JSeo5mYmpuU) доступна по ссылке.

Также дополнительную информацию о машинном обучении простым языком вы можете найти в ноутбуке [**[seminar]ml_basics.ipynb**](./[seminar]ml_basics.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1d95RI9ONwSc4ObiGSDw_euH8B2QuIoxu). 

Очень важно всегда помнить основные **функции потерь**. Их список вы найдете в ноутбуке [**[seminar]loss_functions.ipynb**](./[seminar]loss_functions.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1SGulXic8nNjRZZdAzBX5yUQDMwglKOWF). 

### Pandas

На семинарах мы переходим к изучению инструментов, которые являются основным фокусом данного занятия. 

Pandas - очень популярная библиотека для работы с табличными данными (обычно они записаны в формате .xls или **.csv**). Большинство доступных данных имеют именно такой вид, поэтому Pandas часто используется при подготовке данных. 
	
Для нашего курса будет достаточно познакомиться с основной функциональностью. [**Запись первой части семинара**](https://www.youtube.com/watch?v=-MZgt5pTS4g) даст вам достаточно умений, если одновременно решать [**[seminar]pandas.ipynb**](./[seminar]pandas.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1PsPo1BHd99evSphfE14FbgJWiAj5FU_k).

### Matplotlib

Продолжая изучать полезные инструменты, мы переходим к библиотеке для построения графиков - **Matplotlib**. Далее в курсе **matplotlib** будет использоваться как для построения разнообразных графиков, так и для показа **изображений (картинок)**.

Чтобы разобраться с основами вы, как всегда, можете посмотреть [**запись нашего семинара**](https://www.youtube.com/watch?v=-MZgt5pTS4g) и прорешать [**[seminar]matplotlib.ipynb**](./[seminar]matplotlib.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1R0nKyoZ3ANd4vukogEqM3egPJpvnFq41). 

Cвериться можно с [**[sem_solution]pandas.ipynb**](./[sem_solution]pandas.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1Y5jT0-LBISKJ1MbT_BhXjkKNaEpkgbc6)

Также есть дополнительный ноутбук о matplotlib, который рекомендуется пройти продвинутым слушателям [**extra/[extra_seminar]matplotlib.ipynb**](./extra/[extra_seminar]matplotlib.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/18eQf3-QF0p_LljHkxQfgO7Iz5YUREZHO).

**Примечание**: на семинаре были разобраны только базовые функции Pandas и matplotlib. Чтобы узнать о них больше, вы можете исппрйоти ользовать любой хороший курс по машинному обучению. Например, [курс от сообщества Open Data Science](https://habr.com/ru/company/ods/blog/322626/).

### Домашнее задание

[**[homework]pandas.ipynb**](./[homework]pandas.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1aLOZ4Uw9geV-nn2p2qEPwzDcASV43W3W)и [**[homework]knn.ipynb**](./[homework]knn.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1Zu4WVMiL-wS64c95bdQLNfcqMqFY8qSF) помогут закрепить материал с семинара и лекции. 

Если вы участвуете в курсе "официально", то вы можете проверить ответы и получить оценку в **Canvas**-странице нашего курса. Не слушатели, к сожалению, не имеют возможности свериться, но Вы можете присоединиться к следующей итерации курса как онлайн слушатель (см. ссылки на нашем официальном сайте).
