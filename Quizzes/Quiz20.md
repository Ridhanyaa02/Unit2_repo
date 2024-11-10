# Quiz 20 
# Create a program that produces the graph for the function in Quiz #20 

## Python code 
```.py
import matplotlib
from matplotlib import pyplot as plt
import random
random.seed(1234)
y = int()

def equation(n:int, m:int, s:int):
    x_value = []
    y_value = []

    for i in range(n):
        x = random.randint(0,100)
        y = x ** (0.5 * ((m/s)**2))
        x_value.append(x)
        y_value.append(y)

    return x_value, y_value

x,y = equation(n=10, m=5, s=2)

plt.style.use('ggplot')
plt.plot(x,y, color = 'r', marker="o")
plt.xlabel("Random numbers", fontsize=20)
plt.ylabel("$y=x^{(1/2)(m/s)}$", fontsize=20)
plt.show()
```

## Proof of work 
![image](https://github.com/user-attachments/assets/fb9b688a-f9a2-4e03-adc4-8b9721316573)

## Paper solutions 
# Part b
![image](https://github.com/user-attachments/assets/6d57a3f6-9273-404b-9c36-7cf163b83a4a)
