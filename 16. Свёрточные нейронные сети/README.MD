
# 8. Convolutional Neural Networks

Приветствуем Вас на **восьмом** занятии нашего курса. Сегодня мы перейдем к изучению еще одного типа нейронных сетей --- сверточных. Именно развитие таких сетей произвело революцию в Computer Vision, позволив компьютеру обгонять человека в задачах распознавания объектов.

<p align=center>
  <img src="https://miro.medium.com/max/3288/1*uAeANQIOQPqWZnnuH-VEyw.jpeg" width=700>
</p>

### Лекция: Сверточные нейросети

Сверточные сети так называются, потому что в них используются сверточные слои. Эти слои проводят над картинками операцию, которая в математике называется **свертка**, но такое объяснение слишком сложно и не дает интуитивного понимания работы сверточных слоев. 

Есть намного более простое объяснение, основывающееся на том, что свертка позволяет **узнавать на картинке некоторые паттерны**. Чтобы узнать обо всем этом, предлагаем посмотреть [**запись лекции**](https://www.youtube.com/watch?v=Xul1DS08hSA) ([слайды](./conv_nets.pdf)). Также в поисковике Вы можете найти много других объяснений, если лекции оказалось недостаточно.

### Семинар: Операции свертки и пулинга

Дополнительно объяснение того, как работает свертка, вы можете найти в jupyter-ноутбуке: [**[seminar]convolution_pooling.ipynb**](./[seminar]convolution_pooling.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/16hH-O-mzYyyD0F4QfGQyGjLzEvfdSy9K). Также в этом ноутбуке рассматривается еще один важный слой - слой **пулинга (pooling)**, который позволяет сжимать информацию о картинке. В освоении материала Вам поможет [**запись**](https://www.youtube.com/watch?v=ZxTOUTD0QK8) семинара.

### Семинар: Сверточные нейросети на PyTorch

Теперь пришло время использовать наши теоретические знания и создать свою сверточную нейросеть на PyTorch для классификации датасета CIFAR10: [**[seminar]convnet_pytorch.ipynb**](./[seminar]convnet_pytorch.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1OqQ4r0lo-Mm-6JBmNu9wsD_MfLbWwg7s). С выполнением заданий Вам поможет запись семинара, ссылка на которую уже есть выше. 

Обратите внмиание на то, насколько лучше сверточные нейросети подходят для классификации картинок, чем просто полносвязные (Fully-Connected) нейросети.

### Домашнее задание

Домашняя работа в этом занятии очень объемная, поэтому стоит приступить к ней как можно раньше. Тетрадка [**[homework]cnn.ipynb**](./[homework]cnn.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1J2i64P4KQMC5mkE_bYwP2XuKj7-rISo-)
