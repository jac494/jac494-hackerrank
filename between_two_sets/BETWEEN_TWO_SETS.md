# Between Two Sets

## Instructions

There will be two arrays of integers. Determine all integers that satisfy the following two conditions:

* The elements of the first array are all factors of the integer being considered
* The integer being considered is a factor of all elements of the second array

These numbers are referred to as being between the two arrays. Determine how many such numbers exist.

Example

```txt
a = [2,6]
b = [24,36]
```

There are two numbers between the arrays: 6 and 12.
`6%2=0`, `6%6=0`, `24%6=0` and `36%6=0` for the first value.
`12%2=0`, `12%6=0` and `24%12=0`, `36%12=0` for the second value. Return 2

### Inputs

* m
* n
* a
* b

### Constraints

* 1 <= n,m <= 10
* 

### Sample Input

```txt
2 3
2 4
16 32 96
```

### Sample Output

```txt
3
```

## Notes
