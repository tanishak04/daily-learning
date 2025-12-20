   ````md
```python
st="LinkedIn posts can significantly improve engagement and visibility."
f=open("test2.txt","w")
f.write(st)
f.close()

f=open("test2.txt")
f2=f.read()
print(f2)

