Задание:
Используя топологию распределенной системы и библиотеку межпроцессного
взаимодействия (IPC) из первой лабораторной работы, необходимо реализовать
банковскую систему, описанную выше.
Во время выполнения программы осуществляются переводы денег между счетами.
При завершении на экран выводится таблица с информацией о балансе каждого счета и
полной сумме денег, находящихся на всех счетах, в каждый момент времени t ∈ 0, 1, …, T.
Последняя отметка времени T определяется на момент завершения каждого из процессов
«C» (при получении соответствующего сообщения от процесса «К», см. далее), T ≤
MAX_T