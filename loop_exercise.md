# Solution to loop exercise on Snakify
## 1.Series-1

<img width="297" alt="Series-1" src="https://user-images.githubusercontent.com/82266864/132315809-672bc4a1-a438-4a15-99c9-d19e827aab5d.png">

```py
#program to print all numbers from A to B inclusively.
A= int(input())
B=int(input())
for i in range(B-A+1):
    print(A+i)
#END
```

## 2.Series-2

<img width="669" alt="Series 2" src="https://user-images.githubusercontent.com/82266864/132315841-e0b090c7-82a4-44c3-bc7c-d6da69776dce.png">

```py
#program to print all numbers from A to B inclusively, in ascending order, if A < B, or in descending order, if A ≥ B.
A=int(input())
B=int(input())
if B>A:
    for i in range(A,B+1,1):
        print(i)
else:
    for i in range(A,B-1,-1):
        print(i)
#END
```

## 3.Sum of ten numbers

<img width="304" alt="Sum of ten numbers" src="https://user-images.githubusercontent.com/82266864/132315879-4f355b0a-b242-416a-8ed7-b4b3fb339ffc.png">

```py
#10 numbers are given in the input. Read them and print their sum. Use as few variables as you can.
a=0
for i in range(10):
   a+=int(input())
print(a)
#END
```

## 4.Sum of N numbers

<img width="349" alt="Sum of n numbers" src="https://user-images.githubusercontent.com/82266864/132315919-f72c234d-3840-484e-a91c-6b37cae47f38.png">

```py
#The first line of input contains the integer N, which is the number of integers to follow. Each of the next N lines contains one integer. Print the sum of these N integers.
n= int(input())
t=0
for i in range(n):
    t+=int(input())
print(t)
#END
```

## 5.Sum of cubes

<img width="296" alt="Sum of cubes" src="https://user-images.githubusercontent.com/82266864/132315942-09e66edd-3e19-428d-ba7c-344ff72fce16.png">

```py
#For the given integer N calculate the following sum: 1^3 + 2^3 +...+N^3
a =int(input())
n=0
for i in range(0,a+1,1):
    n+=(i**3)
 
print(n)
#END
```

## 6.Factorial

<img width="328" alt="Factorial" src="https://user-images.githubusercontent.com/82266864/132315970-c54c73d0-f474-4890-8b52-7801452185a2.png">

```py
#In mathematics, the factorial of an integer n, denoted by n! is the following product:
                          n!=1×2×…×n
a=1

for i in range(1,int(input())+1):
    a*=i
print(a)
#END
```

## 7.The number of zeros

<img width="396" alt="The number of zeros" src="https://user-images.githubusercontent.com/82266864/132315993-ad74d680-9c6c-4633-8e5e-35cd8a915703.png">

```py
#Given N numbers: the first number in the input is N, after that N integers are given. Count the number of zeros among the given integers and print it.
a=0
j=int(input())
for i in range(j):
    if int(input())==0:
        a+=1
    else: 
        a+=0
print(a)
#END
```
## 8.Adding factorials

<img width="268" alt="Adding factorials" src="https://user-images.githubusercontent.com/82266864/132316010-597fb47f-0934-4dd6-b00b-043c623428e5.png">

```py
#Given an integer n, print the sum 1!+2!+3!+...+n!.
n=1
sum=0

for i in range(1,int(input())+1):
    n*=i
    sum+=n
print(sum)
#END
```

## 9.Ladder

<img width="369" alt="Ladder" src="https://user-images.githubusercontent.com/82266864/132316029-fab27f92-5cff-477e-ba3c-f320064edca3.png">

```py
#For given integer n ≤ 9 print a ladder of n steps. The k-th step consists of the integers from 1 to k without spaces between them.
n = int(input())
for i in range(1, n + 1):
    for j in range(1, i + 1):
        print(j, sep='', end='')
    print()
    #END
```

## 10.Lost card

<img width="376" alt="Lost card" src="https://user-images.githubusercontent.com/82266864/132316052-19654f93-ba9d-41c3-8375-aed6dd1d75ee.png">

```py
#There was a set of cards with numbers from 1 to N. One of the card is now lost. Determine the number on that lost card given the numbers for the remaining cards.
Given a number N, followed by N − 1 integers - representing the numbers on the remaining cards (distinct integers in the range from 1 to N). Find and print the number on the lost card.
b=0
i= 0
k=0
a=int(input())
for i in range(a-1):
    k+=int(input())
    b+=(i+1)
lost= b+a - k
print(lost)
#END
```
