
# 13. Object detection

Приветствуем Вас на **тринадцатом** занятии нашего курса. Сегодня мы познакомимся с еще одной задачей, которую умеют решать нейронные сети - Object Detection (обнаружение объектов интеерсующих классов на картинке). В ходе занятия Вы познакомитесь с основными архитектурами нейросетей, которые используются для решения этой задачи, а в домашнем задании примените нейросеть YOLOv3 на практике.

<p align=center>
  <img src="https://cdn.filestackcontent.com/PyosrcISSROz1ON9zxhr" width=700>
</p>

### Лекция: Основы детектирования объектов

Существует несколько типов детекторов, они отличаются основной идеей, архитектурой нейросети и функцией потерь. Наиболее популярные детекторы сейчас: **Faster-RCNN**, **SSD** и **YOLO**. Изучить их будет достаточно, чтобы понять основные идеи, использующиеся в Object Detection. 

Узнать об устройстве этих детекторов и метриках качества, традиционно применяющихся в Object Detection, вы можете из [**записи**](https://www.youtube.com/watch?v=ewkSI2cuyoQ) лекции. В конце лекции рассматривается алгоритм YOLOv3, готовую реализацию которого Вы используете в домашнем задании.

### Семинар: TensorFlow Object Detection API

Для практического применения намного удобнее использовать готовые решения, чем писать свои с нуля. В Object Detection есть такое готовое решение - TensorFlow Object Detection API. Научиться с ним работать Вам поможет [**запись**](https://www.youtube.com/watch?v=xHIzyrU1uVM) семинара. 

Как и всегда, Вы получите наибольшую пользу от семинара, если параллельно откроете тетрадку [**[seminar]object_detection.ipynb**](./[seminar]object_detection.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1zaNAUylCD4wKe2pk4YGI1yFIs5IXjx77) и будете постепенно ее просматривать, останавливаясь и используя поисковик, если что-то непонятно.

### Домашнее задание 

В домашнем задании Вам предстоит обучить готовую модель YOLOv3 на свой датасете. Модель написана на TensorFlow,  а не PyTorch, с которым мы работали до сих пор, поэтому Вам может понадобиться небольшое введение в Tensorflow. В этом Вам поможет тетрадка  [**[homework]tensorflow.ipynb**](./[homework]tensorflow.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1Orq_5zAOGvN5MOihonyheXPbdj-NuUHs).  

Если в процессе выполнения задания Вы поймете, что Вам не хватает знаний о TF, то Вы можете дополнительно посмотреть [официальные примеры и туториалы](https://www.tensorflow.org/tutorials).

Теперь пришло время перейти к тетрадке [**[homework]yolov3_detection.ipynb**](./[homework]yolov3_detection.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/12pl46i2MvKCImS1qkiTFwqQVUcM6k-lG). Постарайтесь выполнить все задания, в том числе и дополнительное, потому что оно - самое важное для "реальной" практики. 
