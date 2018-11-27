При решении задачи необходимо было обратить внимание на два момента:

* Сумма температур может достигать 10^14, поэтому должна храниться в типе int64_t.
* Сумма температур может быть отрицательной, поэтому не должна делиться на беззнаковое число при вычислении среднего арифметического.