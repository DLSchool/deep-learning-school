
# 6. PyTorch и Многослойные нейронные сети

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
