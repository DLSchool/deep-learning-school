
# Шестое занятие
Приветствуем Вас на **шестом** занятии нашего курса. Сегодняшнее занятие будет посвящено PyTorch, очень мощному и современному фреймворку, на котором создаются нейронные сети. В конце занятия мы познакомимся с первым видом нейронных сетей - Dense Network.

### План занятия
#### 1. Лекция 
Чтобы узнать общую информацию о многослойных сетях и о том, как с их помощью решать проблему многоклассовой классификации, посмотрите   [**запись**](https://www.youtube.com/watch?v=FSb5vuG6Bkw) лекции. Эта лекция также важна, так как позволяет понять назначение и принцип работы Dense сетей.

#### 2. PyTorch
Существует много разных фреймворков для создания нейросетей, и самый популярный из них - TensorFlow, но в нашем курсе мы будем использовать PyTorch, потому что он намного быстрее развивается и в целом проще в освоении. Его API очень похож на API numpy, поэтому Вам будет легче, если Вы уже понимаете принципы работы numpy и знаете его основные функции.

Чтобы изучить основные функции, которые есть в PyTorch, посмотрите [**запись**](https://www.youtube.com/watch?v=UoBYayBPh84) семинара и выполните задания в тетрадке [**[seminar]pytorch_basics.ipynb**](./[seminar]pytorch_basics.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1Wrur4sqHVO0MQLX0-9ifBsD79HXWUtUF). При изучении таких больших фреймворков может оказаться полезным [шпаргалка](https://pytorch.org/tutorials/beginner/ptcheat.html) по основным функциям, которая находится на официальном сайте PyTorch.

#### 3. PyTorch Neuron
На прошлом занятии Вы создавали свой нейрон с помощью NumPy, теперь пришло время сделать то же самое, но с помощью PyTorch. Тетрадка [**[seminar]neuron_pytorch.ipynb**](./[seminar]neuron_pytorch.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1rKTMDU_zvhqTM7FosQOTd1Nb3Aw-eaD9) , в которую нужно вписать части кода поможет Вам в этом. Также в записи семинара семинарист разбирает, как это сделать. Выполнив тетрадь Вы можете сравнить, насколько различаются реализации на Numpy и PyTorch.

#### 4. PyTorch Fully Connected
Пришло время написать свою первую настоящую нейросеть - полносвязную сеть (Fully Connected или Dense, причем так же называют не только сеть, но слои, из которых она состоит - такие слои, в которых каждый нейрон связан с каждым предыдущим). Как всегда Вы можете использовать тетрадку [**[seminar]mlp_pytorch.ipynb**](./[seminar]mlp_pytorch.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1YQ5EfthNJMW0Nu406w3VJNf4Roi3aA24) с пропущенным кодом, смотря запись семинара в случае трудностей.

#### 5. Домашнее задание
Сегодня домашним заданием будет соревнование на kaggle. Ращобраться с тем, что делать Вам поможет тетрадка [**[homework]fashionmnist_kaggle.ipynb**](./[homework]fashionmnist_kaggle.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/12i5o9-QI4E8l3xLxndLpoLHSaCKsTpkF) (файл sample_submission.csv будет недоступен из Colab, но он есть в этом репозитории). Если Вы официально прослушиваете наш курс, то в зависимости от Вашей точности Вы получите оценку.
