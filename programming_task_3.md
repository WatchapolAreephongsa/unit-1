# HL3. Using the program you created in Task 2, create a program that searches automatically for strange numbers. Can you find a number that will take 10 steps or more?

```py

strange_number = 11
initial = strange_number
step = 1
while step < 11:
    step = 1
    strange_number = initial
    while strange_number>=11:

        strange_number = str(strange_number)
        length = len(strange_number)
        number = 1

        for i in range(length-1):
            int_strange_number= int(strange_number[i])
            number *= int_strange_number
        int_strange_number = int(strange_number[i+1])
        number *= int_strange_number

        step+=1
        strange_number = number
    st = str(initial)
    for i in range(0, len(st)):
        if st[i] == '1' or st[i] == '0' or st[i] == 5:
            initial +=(10**((len(st)- i - 1)))

    initial += 1
print(f"{step},{initial-1}")

```
### Solution = 3778888999
