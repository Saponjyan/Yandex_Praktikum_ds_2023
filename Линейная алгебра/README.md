## Линейная алгебра

проект| задача| стек
:----------------| :--------------:|-------------------------:
Защита персональных данных клиентов|Вам нужно защитить данные клиентов страховой компании «Хоть потоп». Разработайте такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обоснуйте корректность его работы.Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.| Sklearn numpy pandas

## Вывод:

Показатели R2 у предсказаний модели, обученной на исходных признаках и у модели, обученной на признаках, полученных после умножения на обратимую матрицу практически идентичны. Соответственно алгоритм защиты персональных данных путём умножения признаков на обратимую матрицу можно использовать.
