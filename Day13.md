   ````md
```python
a=int(input("enter the number for which you want the table "))
for i in range (1,11):
    b=a*i
    print(f"{a}x {i}={b}")


names = ["Sam", "Ravi", "Sophia", "Anita", "Suresh", "Meena", "Simran", "Vikram", "Sneha", "Priya"]
for i in range(len(names)):
    a=names[i]
    if a[0]=="S":
        print("good morning",a)


n=int(input("input the number "))
i=1
while i<=10:
    print(f"{n} X {i} = {n*i}")
    i=i+1

n=int(input("enter the number "))
for i in range(2,n):
    if(n%i)==0:
        print("nmber is not prime")
        break
else:
        print("number is prime")

 
n=int(input("enter the number "))
sum=0
i=0
while i<=n:
    sum+=i
    i+=1
print(sum)

n=int(input("enter the number "))
fact=1
for i in range (1,n+1):
    fact=fact*i
print(fact)

n=int(input("enter the number "))
print(" "*(n-1))
print("**")
print("*")
