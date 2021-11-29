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

Исполнение доктестов для median_gray():

![Исполнение доктестов для median_gray()](doctest-median_gray.png) 

Все тесты пройдены. Написание тестов на gray_pixelation() слишком тяжело, так как возвращаемое значение - изображение.

---

Результат инспектирования:

![Результат инспектирования](https://github.com/angst-storm/IDE/inspect.png) 

Замечаний к коду нет, помимо дублирования кода в filter.py и filter_with_filename.py (обусловлено прошлыми заданиями).