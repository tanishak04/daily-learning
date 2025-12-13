   ````md
```python
a=int(input("enter the number "))
def factorial(a):
    if a==1 or a==0:
        return 1
    return a*factorial(a-1)
print(factorial(a))