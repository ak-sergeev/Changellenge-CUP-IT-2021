# Changellenge-CUP-IT-2021
Кейс чемпионат Changellenge CUP-IT 2021 по Data science. На нем нужно было решить задачу Text Entailment на примере датасета SNLI. 
Задача следующая: 
Нам даются основная строка, и строка на проверку. Мы знаем, что основная строка - истина. Нужно проверить, не противоречит ли ей строка на проверку.

Датасет для обучения - так же две строки как параметры, как результат - пять независимых оценок, как именно строки взаимосвязаны.
Е - одна следует из другой (1 -> 2)
C - строки противоречат (1 != 2)
N - означает что нет ни contradiction(C), ни entailment(E)
