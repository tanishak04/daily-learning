   ````md
```python
def greatest(a, b, c):
    if a > b and a > c:
        return "a is greatest"
    elif b > a and b > c:
        return "b is greatest"
    else:
        return "c is greatest"

a = int(input("Enter 1st number: "))
b = int(input("Enter 2nd number: "))
c = int(input("Enter 3rd number: "))

print(greatest(a, b, c))


def convert(c):
    f=((9/5) *c )+32
    return f
c=int(input("enter the celcius value "))
print(convert(c))

print("a")
print("b")
print("c", end="")
print("d", end="t")

def sum1(n):
    n= (n*(n+1)/2) 
    return n
n=int(input("enetr the number "))
print(f"the sum of first {n} natural number is, {sum1(n)}")
