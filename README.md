## lab5
This is a repo for labs 5 and 6 of CMPINF 0010. 

# Description
This Lab 5 exercise takes a name and integer input, and determines whether the integer is a prime or not.
It uses a `while` loop to test each integer starting from half of the inputted number (as anything larger than half can't be divisible)
It uses modulus (`%`) to test whether the remainder between the inputted number and the step is 0 or not. If it is 0, it ends the loop.
If it isn't 0, it decreases step by 1. This repeats until the step is 1, in which the loop stops.
After the loop is finished, the program uses `print` to display the results, along with the name input, in a detailed manner.

```
print(f'Hi {name}, your number {num} is {primestat}!')
```

# Members
Minhal Khan, Radley Lettich

## Links
[License](https://github.com/minhal-khan/lab5/blob/main/LICENSE.md)

[Conduct](https://github.com/minhal-khan/lab5/blob/main/CODE_OF_CONDUCT.md)
