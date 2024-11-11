# Quiz 19 
# Create a program that produces n random values from the equation below, where m and s are the other inputs of the function 

## Python code 
```.py
import random
random.seed(1234)

def equation(n:int, m:int, s:int):
    output = "|   X   |      Y      |\n"

    for i in range(n):

        x = random.randint(-100,100)
        y = x * (((m/s) ** 2)/2)
        output += f"| {x:^5} |{y:^12} |\n"

    return output


print(equation(n=5,m=3,s=2))
```

## Proof of work
![image](https://github.com/user-attachments/assets/7707833c-0bd2-4e29-b6fc-0f5995b5c13f)
*Figure 1.1 - Proof of work*

## Paper Solutions 
## Part B 
![image](https://github.com/user-attachments/assets/847ed227-f70c-45f1-a129-5bb5fcf2316b)
*Figure 2.1 - Proof for identity*
