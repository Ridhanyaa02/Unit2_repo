# Quiz 21
# Create a program shows the graph of the parabola for 100 values of x in the interval -10 < x < 10   

## Python code 
```.py
import matplotlib
from matplotlib import pyplot as plt

def graph():
    x = []
    y = []
    n = 100

    for i in range(-10,11):
        x.append(i)
        e = 2 * ((i + 5)**2)
        y.append(e)

    return x,y

x,y = graph()
plt.style.use('ggplot')
plt.plot(x,y,linewidth=2,color="#fb8500")
plt.title("Graph for f(x)")
plt.show()
```

## Proof of work
![image](https://github.com/user-attachments/assets/fbd2ef55-9929-42c6-b102-e60a74ad99f0)


## Paper Solutions 
## Part B
![image](https://github.com/user-attachments/assets/19a4656d-e5e9-48b2-8d17-c3b8513e3a3e)


