# push_swap

Sorting a list of numbers with two stacks and a tiny set of moves (swap, push, rotate, reverse rotate), using as few moves as possible. A 42 Roma Luiss project in C.

The program prints the list of moves that sorts the numbers. Small inputs have their own short routines, bigger ones go through the main algorithm (`algo_rythm*.c`).

## Run it

```bash
make
./push_swap 3 2 5 1 4
```

Count the moves:

```bash
./push_swap $(shuf -i 1-500 -n 100 | tr '\n' ' ') | wc -l
```
