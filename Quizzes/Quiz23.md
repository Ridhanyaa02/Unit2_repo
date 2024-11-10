# Quiz 23
# Create a program that ① show the graph and ②create a linear (H_model = m*t+b) for the data below:

## Python code 
```.py
from matplotlib import pyplot as plt
import numpy as np

plt.style.use('ggplot')
x,y = [],[57.0, 56.0, 57.0, 56.0, 55.0, 55.0, 54.0, 54.0, 54.0, 53.0, 53.0, 54.0, 53.0, 53.0, 52.0, 52.0, 51.0, 51.0, 51.0, 50.0, 50.0, 49.0, 50.0, 49.0, 49.0, 48.0, 49.0, 49.0, 48.0, 48.0, 48.0, 49.0]

for i in range(0,32):
    x.append(i)

m,b = np.polyfit(x,y,1)
y_fit = []
for i in range(0, 32):
    y_fit.append((m * i) + b)

plt.scatter(x,y,linewidth=2,color="#fb8500")
plt.xlabel("time (minutes)")
plt.ylabel("humidity %")
plt.title("Graph showing humidity % over time")
plt.plot(x,y_fit, linewidth=2,color="#0000FF")
plt.show()

```

## Proof of work
![Screenshot 2024-11-10 193213](https://github.com/user-attachments/assets/3226f333-fbf3-4222-90b4-12a48420bd70)

## Paper Solutions 
## Part B 
![image](https://github.com/user-attachments/assets/1fdbccb4-527b-4af2-b814-3a56bd194207)

