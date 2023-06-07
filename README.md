# Project_CV

# Цель проекта: 
Контрольно пропускная система, с распознованием по лицу.

Нейросеть созданая для данного проета принимает на фход две фотографии, размером 150х150 в формате RGB, и определяет вероятность того что на них изображён один человек.

При применении данной нейронной сети на практике можно использовать приложение прототип которого представлен в файле model_test.ipynb, на вход приходит изображение, и сравнивается со всеми изображениями в папке Database, и выдайт ответ найден ли в ней этот человек.

# Стек технологий: 
Python, sklearn, Keras, TensorFlow, Numpy, OpenCV

# Датасет
Собран в открытых истониках, и храница в папке Data/

# Скриншоты
Пример работы нейронки:

Фотографии представленные в базе данных:

![Image alt](https://github.com/DarkVrat/Project_CV/blob/main/screenshots/Screenshot_1.png)

Человек на переданном изображении и имеется в базе данных:

![Image alt](https://github.com/DarkVrat/Project_CV/blob/main/screenshots/Screenshot_2.png)

Человек на переданном изображении отсутствует в базе данных:

![Image alt](https://github.com/DarkVrat/Project_CV/blob/main/screenshots/Screenshot_3.png)

# Ссылки

Модель нейронной сети с весами дающими accuracy=0.99: https://drive.google.com/file/d/1x0lN1JnI2NWGPaBf7imQb3zOzFAc5rWi/view?usp=drive_link

Демонстация работы: https://www.youtube.com/watch?v=A9r3Kv5en3E

Презентация: 
