# Lab 2 | Artificial Intelligence
Knowledge inference in PROLOG
> Date: Falgun 22 | March 6

## Queries and Results
### Knowledge Base 1
Parent of Bob
```
?- parent(X, bob).
X = pam ;
X = tom.
```



### Kowledge Base 2
Was Jeorge I the parent of Charles I?
```
?- parent(jeorge_i, charles_i).
false.
```

Who was Charles I's parent?
```
?- parent(X, charles_i).
X = james_i.
```
Who were the children of Charles I?
```
?- parent(charles_i, X).
X = catherine ;
X = charles_ii ;
X = james_ii.
```

### Knowledge Base 3
Checking factorial of 12
```
?- factorial(12, F).
F = 479001600 ;
false.
```