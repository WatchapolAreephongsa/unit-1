## Kojiro's Month 

```py

def kojiro_months(n):
    months = "JFMAMJJASOND"
    if n <=12 and n>0:
        print(months[n-1])
    else:
        print("FALSE")
kojiro_months(12)

```

## Bee's Es

```py

def bee(a, b):
    c = a+b
    e = 0
    for i in range(len(c)):
        if c[i] == 'e' or c[i] == 'E':
            e+=1
    if e >=3:
        result = "TRUE"
    else:
        result = "FALSE"
    return result
output = bee("ELEVEN", "SEVEN")
print(output)


```

## Reiji Factoria

```py

def Reiji(n):
    a = 1
    for i in range (n):
        a*=(i+1)
    return a

output = Reiji(9)
print(output)

```
## David Division

```py

def david(a,b):
    if a>b:
        c=a//b
    else:
        c = b//a
    return c
output = david(20,6)
print(output)

```

## Michael "asoijaa"

```py

def michael (word,num):

    count = 0
    for i in range(len(word)):
        character = chr(num + 64)
        if word[i]>'Z':
            character = chr(num + 96)
            if word[i] == character:
                count+=1
        else:
            if word[i] == character:
                count += 1
    return count
output = michael("asoijAa",1)
print(output)

```

## Nagisa Weird Average

```py

def nagisa (n:list):
    total = 0
    for i in range(len(n)):
        total += n[i]
    final = total*(i+1)
    return final
output =nagisa([1,3,5])
print(output)

```

## Anju Shift

```py

def anju (word):
    n = ord(word[0])+1
    new = chr(n)
    for i in range(1,len(word)):
        n= ord(word[i])+1
        new += chr(n)
    return new
output = anju('hello')
print(output)

```
