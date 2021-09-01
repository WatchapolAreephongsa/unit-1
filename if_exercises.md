# Solution to if exercise(chapter 3) in snakify

## 1. Minimum of two numbers 

![Minimum num](https://user-images.githubusercontent.com/82266864/131640149-0420f35a-0404-4efc-8b4b-11169f857b3a.png)


```py
# Program to print the smaller number out of 2 given numbers.

num1= int(input())
num2=int(input())
if num1-num2>0:
    print(num2)
else:
    print(num1)
#END
```

## 2. Sign function
![Sign func](https://user-images.githubusercontent.com/82266864/131640179-d72fd382-8790-4498-b480-63277ec58dcc.png)


```py
#For the given integer X print 1 if it's positive, -1 if it's negative, or 0 if it's equal to zero.

x=int(input())
if x>0:
    print(1)
elif x<0:
    print(-1)
else:
    print(0)
#END
```

## 3. Minimum of three numbers
![min  of 3 num](https://user-images.githubusercontent.com/82266864/131640209-58da789a-4acc-494f-be78-29a2ff0745a6.png)

```py
#Given three integers, print the smallest value.

num1=int(input())
num2=int(input())
num3=int(input())
if num1-num2<0 and num1-num3<0:
    print(num1)
elif num2-num1<0 and num2-num3<0:
    print(num2)
else:
    print(num3)
#END
```

## 4. Equal numbers
![Equal num](https://user-images.githubusercontent.com/82266864/131640262-09f26358-e5e5-43ae-be74-2f1f1871fa39.png)


```py
#Given three integers, determine how many of them are equal to each other.
#The program must print one of these numbers: 3 (if all are the same),
#2 (if two of them are equal to each other and the third is different) or 0 (if all numbers are different).

num1=int(input())
num2=int(input())
num3=int(input())
if num1==num2!=num3 or num1==num3!=num2 or num2==num3!=num1:
    print("2")
elif num1==num2==num3:
    print("3")
else:
    print("0")
#END
```


## 5. Rook move
![Rook](https://user-images.githubusercontent.com/82266864/131640305-7bf5aa4a-73de-4c16-b504-c4f3363d35ca.png)


```py
#Given two different cells of the chessboard, determine whether a rook can go from 
#the first cell to the second in one move.

x1=int(input())
y1=int(input())
x2=int(input())
y2=int(input())
if x1==x2 or y1==y2:
    print("YES")
else:
    print("NO")
#END
```


## 6. Chess board-same color
![Chess board(Same color)](https://user-images.githubusercontent.com/82266864/131640349-bacfc6cb-6ebb-40cc-9210-ef0036a5b74d.png)

```py
#Given two cells of a chessboard. If they are painted in one color, print the word YES,
#and if in a different color - NO.

x1=int(input())
y1=int(input())
x2=int(input())
y2=int(input())
if (x1+y1)%2==0 and (x2+y2)%2==0 or (x1+y1)%2!=0 and (x2+y2)%2!=0:
    print("YES")
else:
    print("NO")

#END
```


## 7. King move
![King Move](https://user-images.githubusercontent.com/82266864/131640403-9fd08a2a-fe2e-4fdd-9bfb-4bd8df6533e6.png)


```py
#Chess king moves horizontally, vertically or diagonally to any adjacent cell. 
#Given two different cells of the chessboard, determine whether a king can go from 
#the first cell to the second in one move.

x1=int(input())
y1=int(input())
x2=int(input())
y2=int(input())
if abs(x2-x1)<=1 and abs(y2-y1)<=1:
    print("YES")
else:
    print("NO")
#END
```


## 8. Bishop moves
![Bishop moves](https://user-images.githubusercontent.com/82266864/131640433-1685ae29-5619-4e89-ab57-8a80547123b1.png)

```py
#In chess, the bishop moves diagonally, any number of squares. Given two different squares of the chessboard,
#determine whether a bishop can go from the first to the second in one move.

x1=int(input())
y1=int(input())
x2=int(input())
y2=int(input())
if y2-y1==x2-x1 or x1+y1==x2+y2:
    print("YES")
else:
    print("NO")
#END
```


## 9. Queen move
![Queen move](https://user-images.githubusercontent.com/82266864/131640528-80764bc2-3ead-41c2-a1e1-affaeb28b710.png)


```py
#Chess queen moves horizontally, vertically or diagonally to any number of cells. 
#Given two different cells of the chessboard, determine whether a queen can go from 
#the first cell to the second in one move.

x1=int(input())
y1=int(input())
x2=int(input())
y2=int(input())
if x1==x2 or y1==y2 or abs(x1-x2)==abs(y1-y2):
    print("YES")
else:
    print("NO")
#END
```


## 10. Knight move
![Knight move](https://user-images.githubusercontent.com/82266864/131640554-525fdaba-8be9-4f84-ab22-35398c26b2af.png)


```py
#Chess knight moves like the letter L. It can move two cells horizontally and one cell vertically, 
#or two cells vertically and one cells horizontally. Given two different cells of the chessboard, 
#determine whether a knight can go from the first cell to the second in one move.

x1=int(input())
y1=int(input())
x2=int(input())
y2=int(input())
if abs(x2-x1)==1 and abs(y2-y1)==2 or abs(x2-x1)==2 and abs(y2-y1)==1:
    print("YES")
else:
    print("NO")
#END
```


## 11. Chocolate bar
![Chocolate bar](https://user-images.githubusercontent.com/82266864/131640574-3351ab89-342d-4f7d-90d8-5c2a32c9a0bc.png)

```py
#Chocolate bar has the form of a rectangle divided into n×m portions. 
#Chocolate bar can be split into two rectangular parts by breaking it along a selected straight line on its pattern.
#Determine whether it is possible to split it so that one of the parts will have exactly k squares.

n=int(input())
m=int(input())
k=int(input())
if k%n==0 and k/n<m or k%m==0 and k/m<n:
    print("YES")
else:
    print("NO")
#END
```


## 12. Leap year
![Leap year](https://user-images.githubusercontent.com/82266864/131640636-0d7abbea-8685-43af-88c0-80fd0d3edb91.png)


```py
#Given the year number. You need to check if this year is a leap year. If it is, print LEAP, otherwise print COMMON.
#The rules in Gregorian calendar are as follows:
#     a year is a leap year if its number is exactly divisible by 4 and is not exactly divisible by 100
#     a year is always a leap year if its number is exactly divisible by 400

year=int(input())
if year%400==0:
    print("LEAP")
elif year%100!=0 and year%4==0:
    print("LEAP")
else:
    print("COMMON")
#END
```
