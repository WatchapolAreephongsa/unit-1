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

# Output
<img width="1417" alt="Quiz3" src="https://user-images.githubusercontent.com/82266864/144792508-a9eb9a46-ed5b-4212-8cf3-8a3e6fabdf39.png">

