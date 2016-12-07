# Kink.com Coding Challenge - Count Down

## Challenge 1

### Goal
Create a function that takes an integer and counts down to zero `0` printing each iteration.

## Example
If the given integer is `5`, the output should be:

```
5
4
3
2
1
0
```

## Challenge 2

### Goal
Create a function that takes a single `alpha` (`a-z`) character and counts down to `a` printing each iteration.

### Example
If the given character is `f`, the output should be:
```
f
e
d
c
b
a
```

## Challenge 3

### Goal
Create a function that takes a string of `alpha` characters (`a-z`, no spaces) and counts down each character in the string until all of the characters are `a`.

### Example
If the given string is `food`, the output should be:
```
food
eood
dood
cood
bood
aood
znod // Notice 'a' -> 'z' and 'o' -> 'n'
ynod
xnod
...
bdod
adod
zcod // Notice 'a' -> 'z' and 'd' -> 'c'
...
aaaa
```

### Bonus!
Instead of decreasing the first character in the string, decrease from the last character.
```
food
fooc
foob
fooa
fonz // Notice 'o' -> 'n' and 'a' -> 'z'
fony
fonx
...
fonb
fona
fomz // Notice 'n' -> 'm' and 'a' -> 'z'
...
aaaa
```

## Guidelines
- All code should be written in vanilla JavaScript (nodejs 6) or Python (python 2.7).
- If you use Javascript, please refrain from using ecmascript 2015 features (fat arrows, let, const, class, etc.)
- Please do not use any third party libraries or plugins.
- Documentation and maintainability is a plus.

### Time Allotment
We respect your time and would prefer you not spend more than 3-5 hours on these challenges. Feel free to include code comments to indicate any features you don't have time to implement.
