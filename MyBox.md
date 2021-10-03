```py
def Box1(letter1, letter2, letter3):
    if letter1 > 'Z':
        number1 = ord(letter1)-96
    else:
        number1 = ord(letter1)-64
    if letter2 > 'Z':
        number2 = ord(letter2)-96
    else:
        number2 = ord(letter2)-64
    if letter3 > 'Z':
        number3 = ord(letter3)-96
    else:
        number3 = ord(letter3)-64
    total = (number1)* (number2)*(number3)
    return total
#change letter to number A = a using ord and then times all 3 values

def Box2(num1,num2):
    n1 = str(num1)
    n2 = str(num2)
    n = n1+n2
    number = int(n)
    final = number % 14
    return final
#Stick both number together and then fiond the remainder after divide by 7

def Box3(a,b):
    to = (a+b)%52
    if to<=13:
        card = to%13
        c = "Clover"
    if to>13 and to<=26:
        card = to%13
        c = "Diamond"
    if to>26 and to<=39:
        card = to%13
        c = "Spade"
    if to>39:
        card = to%13
        c = "Heart"
    if card == 0:
        card = "King"
    if card == 11:
        card = "Jack"
    if card == 1:
        card == "Ace"
    if card ==12:
        card = "Queen"
    return f"Your card is {card} {c}."

#List of country in alphabetical order

print(Box1('U','w','C'))
print(Box1('A','b','c'))
print(Box1('D','O','G'))
print(Box1('c','o','w'))
print(Box2(Box1('U','w','C'),Box1('A','b','c')))
print(Box2(Box1('D','O','G'),Box1('c','o','w')))
output = Box3(Box2(Box1('U','w','C'),Box1('A','b','c')),Box2(Box1('D','O','G'),Box1('c','o','w')))

print(output)
```
