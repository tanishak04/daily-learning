   ````md
```python
l=[]
a=int(input("enter number "))
b=int(input("enter number "))
c=int(input("enter number "))
d=int(input("enter number "))
l.append(a)
l.append(b)
l.append(c)
l.append(d)
l.sort()
print(l[3])
         

m1=int(input("enter marks 1 "))
m2=int(input("enter marks 2 "))
m3=int(input("enter marks 3 "))
m4=int(input("enter marks 4 "))
sum=m1+m2+m3+m4
if((m1>(33/100)*m1) and (m2>(33/100)*m2) and (m3>(33/100)*m3) and (m4>(33/100)*m4) and (sum>(40/100)*400)):
    print("passed")
else:
    print("fail")    


str=input("enter the sentence ")
if "subscribe" in str:
    print("its  spam")
else:
    print("mot spam")
 

a=input("enter the name ")
if len(a) >=10:
    print("your name has 10 char")
else:
    print("name dosent has 10 chr")

a=int(input(" enter you marks:"))
if 80<=a<=90:

    print("A")
elif 70<=a<=80:
    print("B")
elif 60<=a<=70:
    print("C")
elif 50<=a<=60:
    print("D")
else:
    print("F")

text = "Python is a powerful programming language that is easy to learn and widely used in data science, web development, and automation."
if "PyThon".lower() in text.lower():
    print("python is in str")
else:
    print("nhi h ")

