# Quiz 24 
# 

## Python code 
```.py
from matplotlib import pyplot as plt

data =  {
'x': [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19],
'y': [24, 1, 2, 25, 26, 21, 23, 34, 49, 2, 19, 32, 7, 17, 36, 7, 45, 28, 40, 46]
}

if 'title' in data:
    print(data['title'])
else:
    data['title'] = "Quiz_data_science"

plt.style.use('ggplot')
plt.plot(data['x'],data['y'],linewidth = "2")
plt.xlabel('X')
plt.ylabel('Y')
plt.title(data['title'])
plt.show()
```

## Proof of work 
![image](https://github.com/user-attachments/assets/638d654c-0d1f-4ab5-9334-465564ab5ab4)
*Figure 1.1 - Proof of work* 

## Paper solutions 
## Part B
![image](https://github.com/user-attachments/assets/f0d90581-5321-4182-8e5a-e5c5d6e271dc)
*Figure 2.1 - Converting RBG to Hex* 
 