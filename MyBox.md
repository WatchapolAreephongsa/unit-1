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
    country = ['Australia', 'Brazil','China', 'Denmark','Egypt', 'Finland','Greece', 'Hong Kong','India', 'Japan','Kenya','Luxembourg', 'Malaysia','New Zealand', 'Oman', 'Portugal','Qatar', 'Russia', 'Switzerland','Thailand','USA', 'Vietnam','UWC','ISAK' ,'Yamen','Zambia']
    to = (a+b)%25
    country = country[to]
    return country
#List of country in alphabetical order



output = Box3(Box2(Box1('A','U','P'),Box1('A','B','C')),Box2(Box1('C','A','T'),Box1('D','O','G')))

print(output)

```
