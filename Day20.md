````md
```python
with open("c:\\Users\\mohan\\python\\cwharry\\ch9\\test.txt") as f:
    a=f.read()
if "nova" in a:
    print("file has twikle")
else:
    print("false")

import random
comp=random.choice([1,2,3,4,5,6])
with open(r"c:\Users\mohan\python\cwharry\ch9\highscore.txt","r") as f:
    win=f.read()
    a3=win.count("w")
    print(f"highscore is {a3}" )
a=int(input("guuess the number "))
if a>6:
    print("choose a number smaller then 6")
else :
    def game():
        if a==comp:
            print(f"you won the comp guessed {comp}")
            with open(r"c:\Users\mohan\python\cwharry\ch9\highscore.txt", "a+") as f:
                f.write("w ")
                f.seek(0)
                data=f.read()
                a1=data.count("w")
                print(f"you won {a1} times:")

                
        else:
            with open(r"c:\Users\mohan\python\cwharry\ch9\highscore.txt","a+") as f:
                f.write("l ")
                f.seek(0)
                data=f.read()
                a2=data.count("l")  
                print(f"you lost {a2} times")
                
    game()



def table(n):
        with open(f"tables/table of {n}.txt", "w") as f:
            for i in range (1,11):
                line=f"{n} x {i} = {n*i}\n"
                f.write(line)


for i in range(2,21):
    table(i)
