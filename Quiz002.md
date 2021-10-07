## Find the difference between biggest and smallest number in 3 numbers

```py

def quiz (A,B,C):
    if A<B<C:
        result = C-A
    if B<C<A:
        result = A-B
    if C<B<A:
        result = A-C
    if C<A<B:
        result = B-C
    if B<A<C:
        result = C-B
    if A<C<B:
        result = B-A
    return result
print(quiz(3,9,6))

```
