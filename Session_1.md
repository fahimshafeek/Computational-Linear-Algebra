## PSEUDOCODE FOR LINEAR ALGEBRA
```python
FUNCTION matrix_Solution(A,b):
    Creat augmented matrix: K=[A|b]
    Reduce in Row Reduced Echelon Form
    Rank = No of non zero rows in RREF
    If Rank(K)!=Rank(A):
        printf("System is inconsisten")
    Else
        Solve using back substitution
END FUNCTION
```
$$A=\begin {pmatrix}
1&2&3\\
3&4&5\\
5&6&7\\
\end{pmatrix}$$
