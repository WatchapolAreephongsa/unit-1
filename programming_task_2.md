# HL2.Strange Numbers: Given a number as a String N. Multiply all of its digits, and repeat the same with the product obtained till the product consists of only one digit. Output the number of steps taken to do so. 
 ```py
 
strange_number = int(input("Please input your number: "))
print("")
first_number = strange_number
step =1

while strange_number>=10:
    strange_number = str(strange_number)
    length = len(strange_number)
    number = 1
    print(f"step{step}: ", end='')
    
    for i in range(length-1):
        int_strange_number= int(strange_number[i])
        number *= int_strange_number
        print(int_strange_number, end='*')
        
    int_strange_number = int(strange_number[i+1])
    number *= int_strange_number
    print(int_strange_number, end=' = ')
    step+=1
    strange_number = number
    print(f"{strange_number}")
    print('')
    
print(f"The final product of the multiplication of all digits until there is only 1 digit left of {first_number} is {strange_number} which take {step-1} steps.")
 
 ```
