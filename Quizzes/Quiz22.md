# Quiz 22
# Create a program shows the graph of the function below for 100 values of x in the interval -10 < x < 10 

## Python code 
```.py
import matplotlib
from matplotlib import pyplot as plt

plt.style.use('ggplot')
start = -10
step = 0.01
x,y = [],[]


for i in range (int(20/step)): #20 = -10 to 10  
    x_value = start + step*i
    y_value = abs(x_value)
    x.append(x_value)
    y.append(y_value)


plt.plot(x,y,linewidth=2,color="#fb8500")
plt.xlabel('x')
plt.ylabel('y = |x|')
plt.title('Graph for the parabola y = |x|')
plt.show()

```

## Proof of work
![image](https://github.com/user-attachments/assets/82b1668c-452b-443e-86ba-64dbc4dd80fb)


## Paper Solutions 

## Part B
![image](https://github.com/user-attachments/assets/bbff9b6d-9476-4a14-b196-bf1e39b36f9b)
