## (HL) Given an integer N, show 100 integers with the repeating pattern 0 to N-1, 0 to N-1... and print the addition of the number.

```py

def rangePatternN(n):
    num = 0
    sum = 0
    set = ""
    for i in range (99):
        if num == n:
            num = 0
        str_num = str(num)
        set += str(num) + ", "
        sum+= num
        num+=1
    set += str(num)
    return f'''{set}  
{sum}'''


output = rangePatternN(17)
print(output)

```
