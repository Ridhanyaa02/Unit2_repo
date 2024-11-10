# Quiz 18
# Using the function that produces the table of Truth for 3 inputs, add a column for the boolean equation

## Python code
```.py
def truthtable():
    x = 1
    y = 1
    z = 0

    table = "A | B | C | AB + not B + not CB|\n"
    for i in range(0,8):
        x = int(not(x))
        if i % 2 == 0:
            y = int(not(y))
        if i >= 4:
            z = 1

        AB = z and y
        CB = x and y
        e = int(AB or not(y) or not(CB))
        table += f"{z} | {y} | {x} |          {e}         |\n"


    return table

print(truthtable())
```
## Proof of work 
![image](https://github.com/user-attachments/assets/87253c7e-cdc2-40e1-b9be-3f02a3ec9d1e)

## Paper solutions 

## Part B 
### Truth Table 
![image](https://github.com/user-attachments/assets/a8d4d60c-fbc5-4aa1-b1c0-4dfdff740f55)
### Circuit 
![image](https://github.com/user-attachments/assets/b6167612-ca8a-4591-8ba2-1622f7c4dd1f)

