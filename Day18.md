   ````md
```python
f=open("c:\\Users\\mohan\\python\\cwharry\\ch9\\test.txt")
line=f.readline()
while(line!=""):
    print(line)
    line=f.readline()
f.close()
    