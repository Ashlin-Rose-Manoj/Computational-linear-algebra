## Psuedocode for linear algebra

```python
FUNCTION solution(A,b):
    create Augmented matrix :K=[A|b]
    reduce in raw reduced echelon form
    rank=no of non zero rows of RREF
if rank(K)!=rank(A):
      print( system is inconsistent)
ELSE IF:
      solve using back substitution
END FUNCTION
```

$$A=\begin {pmatrix}
      1&2&3\\
      3&4&1\\
      6&5&4\\
      \end{pmatrix}$$
   
