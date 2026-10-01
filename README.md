Домашнее задание по ПП №4:

Таблица 1, со sleep
<img width="1020" height="140" alt="image" src="https://github.com/user-attachments/assets/9ed23e5c-abe9-40b1-bbae-2b29aa85c993" />

Таблица 2, со blackHole
<img width="1022" height="143" alt="image" src="https://github.com/user-attachments/assets/9e4bcd7f-6267-498e-94f7-0041a060c215" />

Выводы:
1) Метод "Thread per task" тратит много времени на подготовку к вычислениям.
2) При распределении задач способом "Periodic", в методе "Round Robin" все трудоемкие процессы ложатся на один поток, из-за чего тратится много времени на вычисления.
3) Методы "Work Stealing" и "FixedThreadPool" относительно одинаково справляются с распределением нагрузки на потоки.
