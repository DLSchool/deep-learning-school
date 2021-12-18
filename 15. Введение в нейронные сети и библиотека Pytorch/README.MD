
### 15. Введение в нейронные сети и библиотека Pytorch

Сегодняшнее занятие будет очень насыщенным, потому что мы изучим важную для программирования парадигму - **ООП**, напишем свой первый **нейрон**, узнаем несколько новых **функций потерь** и что такое **функции активации**.

<p align=center>
  <img src="https://cs231n.github.io/assets/nn1/neuron_model.jpeg" width=500>
</p>

### ООП в Python

Перед изучением основного материала ознакомьтесь с основными моментами Объектно Ориентированного Программирования в Python. Если до этого Вы проходили хороший курс по Python, то сразу переходите дальше, иначе вы можете посмотреть начало [**записи семинара**](https://www.youtube.com/watch?v=gsPbqq-HYfg), выполнив задания в тетрадке [**[seminar]oop.ipynb**](./[seminar]oop.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1d6OLYtrd7_M0rNx3sjBWNo9Lrkw2IPYM). После выполнения можно свериться с ответами в решенной тетрадке [**[sem_solution]oop.ipynb**](./[sem_solution]oop.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1b7FvehsBF4pR1Eep9XNJopU-Ou2Vbzo6). 

### Лекция: Устройство нейрона в машинном обучении

Начать стоит с просмотра лекции: информация из нее поможет дальше понимать, что из себя представляет код, который Вы пишете. Лектор подает идеи, отталкиваясь от линейных моделей, которые мы изучили ранее, поэтому вам стоит повторить основные моменты из предыдущего занятия. [**Запись лекции**](https://www.youtube.com/watch?v=7U1Z39tFyTo) и её [**слайды**]([lecture]neuron.pdf).

### Семинар: Перцептрон 

Теперь пришло время написать свой первый **перцептрон**, о котором было рассказано в лекции. Для этого откройте тетрадку [**[seminar]perceptron.ipynb**](./[seminar]perceptron.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1TW68wShY8MNGeTMMU_hQjIlDfMEHtn_7) и напишите недостающий код. Вам может помочь [**запись семинара**](https://www.youtube.com/watch?v=gsPbqq-HYfg) (сразу после ООП). Свериться можно с [**[sem_solution]perceptron.ipynb**](./[sem_solution]perceptron.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/16xNAwgeMrao-YfdjES0ZukPgz4wMzPbZ)

### Семинар: Нейрон

Пришло время написать свой **нейрон**. По сути, для этого нужно просто изменить функцию активации в перцептроне. Предлагаем дописать недостающий код в [**[seminar]neuron.ipynb**](./[seminar]neuron.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1KkDoa7X46koYVzL48ZNDcDlfDL3XeiQx). Разобраться с непонятными моментами вам помогут комментарии и пояснения внутри. 

После написания вы можете свериться с [**[sem_solution]neuron.ipynb**](./[sem_solution]neuron.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1DSF3FuRDbyJI6RVZl0Z0T0OXiGbC5AO3)

### Семинар: LogLoss

Как мы и обещали, пришло время узнать про новую функцию потерь - **LogLoss**. Для изучения досмотрите до конца запись семинара и решите ноутбук [**[practice]neuron_logloss.ipynb**](./[pactice]neuron_logloss.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1EAvKdylm_OUEs9PSK0gyAuXD0mXI8Q4Q).

### Домашнее задание

В качестве домашнего задания Вам предстоит разобраться с различными функциями активации: [**[homework]activations.ipynb**](./[homework]activations.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1N6PESAeWC1WbRdfKeSFf-r5M4-1mMuqo).


### PyTorch и Многослойные нейронные сети

Приветствуем Вас на **шестом** занятии нашего курса. Сегодняшнее занятие будет посвящено **PyTorch**, очень мощному и современному фреймворку, на котором создаются нейронные сети. В конце занятия мы познакомимся с первым видом нейронных сетей -- **Multi-Layer Perceptron (MLP)**, или **Fully-Connected Network (FC)**, по-русски **Полносвязные нейросети**. 

<p align=center>
  <img src="https://www.machinelearningmastery.ru/img/0-953466-715076.png" width=400>
</p>

### Лекция: Многослойные нейросети

Чтобы узнать общую информацию о многослойных сетях и о том, как с их помощью решать проблему многоклассовой классификации, посмотрите [**запись лекции**](https://www.youtube.com/watch?v=FSb5vuG6Bkw).

### PyTorch: Основы

Существует много разных фреймворков для создания нейросетей (например, **TensorFlow**), но в нашем курсе мы будем использовать **PyTorch**, потому что он намного быстрее развивается и в целом проще в освоении. Его API очень похож на API NumPy, поэтому Вам будет легче, если вы уже понимаете принципы работы NumPy и знаете его основные функции.

Предлагаем посмотреть [**запись семинара**](https://www.youtube.com/watch?v=UoBYayBPh84) и выполнить задания в [**[seminar]pytorch_basics.ipynb**](./[seminar]pytorch_basics.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1Wrur4sqHVO0MQLX0-9ifBsD79HXWUtUF). 

При изучении таких больших фреймворков может оказаться полезной [шпаргалка по основным функциям](https://pytorch.org/tutorials/beginner/ptcheat.html), которая находится на официальном сайте PyTorch.

### PyTorch: Один нейрон

На прошлом занятии вы создавали свой нейрон с помощью NumPy, теперь пришло время сделать то же самое, но с помощью PyTorch. Jupyter-ноутбук [**[seminar]neuron_pytorch.ipynb**](./[seminar]neuron_pytorch.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1rKTMDU_zvhqTM7FosQOTd1Nb3Aw-eaD9) поможет Вам в этом, а в записи семинара (ссыка выше) семинарист уже разбирает, как ее полностью выполнить. Выполнив тетрадь, вы можете сравнить, насколько отличаются реализации на NumPy и на PyTorch.

### PyTorch: Многослойная полносвязная нейросеть (Fully Connected, FC)

Пришло время написать свою первую настоящую нейросеть - полносвязную сеть (еще называют Fully Connected, или Dense, как и ее лиейные слои). Как всегда, вы можете использовать jupyter-ноутбук [**[seminar]mlp_pytorch.ipynb**](./[seminar]mlp_pytorch.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1YQ5EfthNJMW0Nu406w3VJNf4Roi3aA24) с пропущенным кодом, смотря запись семинара в случае трудностей.

### Домашнее задание

Сегодня домашним заданием будет соревнование на Kaggle. Разобраться с тем, что делать, вам поможет ноутбук [**[homework]fashionmnist_kaggle.ipynb**](./[homework]fashionmnist_kaggle.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/12i5o9-QI4E8l3xLxndLpoLHSaCKsTpkF) (файл sample_submission.csv будет недоступен из Google Colab, но он есть в этом репозитории). Если вы официально прослушиваете наш курс, то в зависимости от вашей точности вы получите оценку.

