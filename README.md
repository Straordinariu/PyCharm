Время выполнения filter.py: 

![Время работы filter.py](filter-profile.png) 

Время выполнения old_filter.py: 

![Время работы old_filter.py](old_filter-profile.png) 

Согласно этим результатам, filter.py выполнялся дольше old_filter.py. Это можно объяснить тем, что 98.2% времени выполнения filter.py было затрачено на ввод данных.


Время выполнения filter_with_filename.py:

![Время выполнения filter_with_filename.py](filter_with_filename-profile.png) 

Благодаря исключению input, время выполнения filter_with_filename.py сократилось значительно относительно filter.py. Также filter_with_filename.py эффективней old_filter.py благодаря оптимизациям (в первую очередь, матричным преобразованиям). 

Благодаря исключению input, время выполнения filter_with_filename.py сократилось значительно относительно filter.py. Также filter_with_filename.py эффективней old_filter.py благодаря оптимизациям (в первую очередь, матричным преобразованиям). 

---

Изображения:

Исходное:

![Исходное изображение](test_img.jpg) 

Результат работы old_filter.py:

![Результат работы old_filter.py](old_result.jpg) 

Результат работы filter.py:

![Результат работы old_filter.py](result.jpg)

---

Исполнение доктестов для median_gray():

![Исполнение доктестов для median_gray()](doctest-median_gray.png) 

Все тесты пройдены. Написание тестов на gray_pixelation() слишком тяжело, так как возвращаемое значение - изображение.

---

Результат инспектирования:

![Результат инспектирования](inspect.png) 

Замечаний к коду нет, помимо дублирования кода в filter.py и filter_with_filename.py (обусловлено прошлыми заданиями).

---

Работа с отладчиком.

Тип изображения (JPEG, выделено):

![Тип изображения](image-format.png) 

Высота изображения (933, выделено):

![Высота изображения](image-height.png) 

Ширина изображения (934, выделено):

![Ширина изображения](image-width.png) 

Размер блока (10):

![Размер блока](block-size.png) 

Число градаций серого (5):

![Число градаций серого](gradations-count.png) 