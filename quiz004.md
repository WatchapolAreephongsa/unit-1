Write a funciton that receives an integer N, and returns all its factors.

[HL] show also the addition of the factors show if the same as N

```py

def perfectN (n):
    factor = []
    total = 0
    for i in range (n-1):
        if n %(i+1) == 0:
            factor.append (i+1)
            total += i+1
    if total == n:
        result = "TRUE"
    else:
        result = "FALSE"
    return factor,result
output = perfectN(6)
print(output)

```
