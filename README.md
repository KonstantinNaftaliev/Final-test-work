# Задача:

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

# Решение:

Создается два массива: изначальный и второй той же длины, который будет состоять из данных, удовлетворяющих условия. Создается цикл, который проверяет данные массива на их длину <= 3 и переносит их или пропускает во второй массив. Индекс первого массиво постепенно увеличивается на 1 и блокается, когда достигает длины заданного массива номер 1.