Последовательно, итеративно, шаг за шагом, step-by-step, pеализуйте:    

1. Версию процессора, работающего с именами команд (push, pop, add, sub, mul, div, sin, cos, sqrt). Команды достают свои аргументы из стека (кроме push) и кладут в стек результат операции;

2. Версию процессора, работающего с кодами команд, загружаемых в оперативную память процессора, ассемблер и дизассемблер для него;

3. Версию процессора с регистрами (ax, bx, cx, dx, whatever). Очень советую тут оглядеться вокруг и посмотреть, какие есть вообще процессорные архитектуры, и, может быть, как-то по-своему обойтись с регистрами;

4. Версию процессора с условными и безусловными переходами. 

Команды переходов такие:

    jmp - jump, безусловный переход
   
    je  - jump if equal, переход, если числа равны
   
    jne - jump if not equal, переход, если числа не равны
   
    ja  - jump if above, переход, если одно число больше другого
 
   
Протестируйте процессор на задачах решения квадратного уравнения
   
