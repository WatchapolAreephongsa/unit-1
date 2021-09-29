
<img width="907" alt="MB" src="https://user-images.githubusercontent.com/82266864/135253605-12e48b05-2807-4afa-aa2e-62c2885f6980.png">
## Mystery Box 1

``` py

def mystery_box1(word, boolean):
    k = str(word)
    w = k[-1]
    if boolean == False:
        a = k.upper()
        m = a[0] + a[1:-1].lower()
        for i in range(len(k), 1, -1):
            w += m[i - 2]
        return w
    if boolean == True:
        a = k.lower()
        for i in range(len(k),1,-1):
            w += a[i-2]
        return w
output = mystery_box1( 'Hello' ,False)

print(output)

```


## Mystery Box 2

```py

def mystery_box2(mail):
    i = 0
    first = mail[0]
    while mail[i+1]!= '.':
        first+=mail[i+1]
        i+=1
    if mail[i+1] == '.':
        last = mail[i+2]
        while mail[i+3] !='@':
            last+= mail[i+3]
            i+=1
    if mail[i+3] == '@':
        address = mail[i+4:-1] + mail[-1]

    f= first.upper()
    l = last.upper()
    first = f[0]+first[1:-1] + first[-1]
    last = l[0] + last[1:-1] + last[-1]
    name = f"{first} {last}"
    print(name)
    return address

output = mystery_box2('aup.pu@gmail.com')
print(output)

```


## Mystery Box 3

```py

def mystery_box3(n1,n2,n3):
    in1 = n1
    in2 = n2
    in3 = n3
    m = n1*n2*n3
    while n3 < m and n1!= n2 or n2!= n3 or n3!=n1:
        if n1< n2 or n1<n3:
            n1+= in1
        if n2<n3 or n2<n1:
            n2+= in2
        if n3<n2 or n3<n1:
            n3+= in3
    return n3

output = mystery_box3(18,4,7)
print(output)

```


## Mystery Box 4

```py

def mystery_box4(n1,n2,n3,n4,n5,n6,n7):
    n4 = 0
    n7 = 0
    total = n1+n2+n3+n4+n5+n6+n7
    avg = total/5
    return avg
output = mystery_box4(5,6,3,8,1,7,9)
print(output)

```
