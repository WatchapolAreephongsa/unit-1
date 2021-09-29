```py
def box(primenumber):
    count = 0
    number = 3
    prime = '2 '
    for i in range(primenumber-1):
        num = 2
        count_old = count
        while count_old == count:
            if num == number:
                numstr = str(number)
                prime += f"{numstr} "
                count+=1
            if number % num == 0:
                number += 1
                num = 2
            if number % num != 0:
                num+=1
    return prime


output = box(15)
print(output)
```
