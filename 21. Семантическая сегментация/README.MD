
# 11. Neural Image Segmentation

Приветствуем Вас на **одиннадцатом** занятии нашего курса. Сегодня мы познакомимся с еще одной задачей, которую успешно решают нейронные сети - **сегментацией** (выделением на картинке областей, на которых находится интересующий объект). Сегодняшнее занятие состоит из двух семинаров.

<p align=center>
  <img src="https://www.cityscapes-dataset.com/wordpress/wp-content/uploads/2015/07/tuebingen00.png" width=600>
</p>

### Данные

Перед тем, как приступить к основной работе, Вам понадобятся данные для обучения модели. Их можно скачать с гугл диска по ссылке [**data.zip**](https://drive.google.com/file/d/1_c8tw7wOgGNXg7ubRwTxzWBoDSsvPpMZ/view?usp=sharing).

### Нейросетевая сегментация изображений

В сегодняшнем занятии вместо PyTorch мы будем использовать другой фреймворк - Keras. Для его работы также необходим установленный фреймворк TensorFlow. Если вы хотите обучать всё на своем компьютере, то убедитесь, что для всех библиотек правильно настроена работа с GPU, иначе это займет очень большое время. В противном случае Вы можете использовать Google Colab.

Разобраться с сегментацией Вам поможет [**запись семинара**](https://www.youtube.com/watch?v=OWK8VlgJM4I) и jupyter-ноутбук, который использовал семинарист: [**[seminar]segmentation.ipynb**](./[seminar]segmentation.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1Uy0RS3cme0_v7ytUv4I-vSWde5NgpiBQ). Веса получившейся на семинаре модели лежат [здесь](https://drive.google.com/file/d/160zQcHMxiOSs9rpsjvJRg0YGcyyhO5yM/view?usp=sharing).

### Домашнее задание 

Вам предстоит попытаться улучшить модель сегментации. Для этого Вы можете изменять разные параметры модели и обучения: [**[homework]segmentation.ipynb**](./[homework]segmentation.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1A5rtbZCThnvKgRWTloPXcblKq5BD-8nd). 
