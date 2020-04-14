
# 7. Neural Networks practice

Приветствуем Вас на **седьмом** занятии нашего курса. Сегодняшнее занятие будет посвящено практике обучения нейронных сетей. Оно состоит из 2 семинаров, на каждом из которых мы работаем со своим датасетом: **CIFAR10** на первом семинаре и **notMNIST** на втором. Все сегодняшнее занятие посвящено практике и поэтому очень важно.

<p align=center>
  <img src="https://img.tsn.ua/cached/1533895030/tsn-0836864a16c9e8e7a60a1868506671d8/thumbs/1200x630/2a/aa/239f01f54044aff63de410b0d117aa2a.jpg" width=600>
</p>

### CIFAR10

CIFAR10 - один из датасетов-бенчмарков, на которых тестируются новые разработки в области глубокого обучения. Любой человек, который занимается этой областью, должен быть с ним знаком. Модели, которые мы будем обучать сегодня, очень простые. Основное, чему Вы должны научиться - шагам, которые присутствуют в обучении нейросетей.

Самой главной частью урока является jupyter-ноутбук [**[seminar1]cifar10.ipynb**](./[seminar1]cifar10.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1md1mT_-9hUQR0moK7koHPdMRLKeNdlS5), именно в ней Вам предстоит тренировать нейросеть. Разобраться в ней вам поможет [**запись первого семинара**](https://www.youtube.com/watch?v=sODip3gxeyQ), целиком посвященного обучению этой сети.

### notMNIST

Вторым датасетом, с которым Вам предстоит работать, является notMNIST (также очень известный датасет). Большинство шагов  в обучении будут теми же, второй датасет нужен для закрепления и знакомства с ним. Вы можете начать в ноутбуке [**[seminar2]notmnist.ipynb**](./[seminar2]notmnist.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1reFpIeEh8r2Gzi6ePggyHfuHYwgG3B_e), используя [**запись второго семинара**](https://www.youtube.com/watch?v=h9bLT3c4_xw). 

В этом ноутбуке используется уже разделенный на train/test датасет, он не будет доступен в Google Colab изначально. Вы можете скачать его с репозитория и добавить в Colab любым удобным способом, или запустить все у себя на компьютере. Ссылки на датасеты - [**notMNIST_train**](https://drive.google.com/file/d/1mvcy8yBJ64rO26C7LC3H4hQXM40EDWau/view?usp=sharing) и [**notMNIST_val**](https://drive.google.com/file/d/1Tm-5_2-OrakO0KJefqZBZqoF4dmFQyol/view?usp=sharing).

### Домашнее задание

В качестве домашнего задания вам предстоит попробовать новую технику регуляризации -- **Dropout**. Эта техника очень полезна и используется почти в каждой современной нейросети. Чтобы изучить ее, выполните jupyter-ноутбук [**[homework]dropout_regression.ipynb**](./[homework]dropout_regression.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1m_s1QmSSQtC3Bn0U9PwDV8DXRI23lMvt)
