
# 5. Один нейрон и ООП в Python

Приветствуем Вас на **пятом** занятии нашего курса. Сегодняшнее занятие будет очень насыщенным, потому что мы изучим важную для программирования парадигму - **ООП**, напишем свой первый **нейрон**, узнаем несколько новых **функций потерь** и что такое **функции активации**.

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
