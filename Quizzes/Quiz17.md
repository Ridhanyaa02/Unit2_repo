# Quiz 17 
## Create a function that produces the table of Truth for 3 inputs:

## Python code 

```.py
def truthtable():
    x = 1
    y = 1
    z = 0

    table = "A | B | C\n"
    for i in range(0,8):
        x = int(not(x))
        if i % 2 == 0:
            y = int(not(y))
        if i >= 4:
            z = 1

        table += f"{z} | {y} | {x}\n"


    return table

print(truthtable())

```

## Proof of work 
![image](https://github.com/user-attachments/assets/e53c03f7-e7b6-4f34-97c1-7c7d94db004f)
*Figure 1.1 - proof of work*

## Paper solutions 

## Part B 
### Truth Table 
![image](https://github.com/user-attachments/assets/dc0b696a-eb44-4acb-adda-91dbbdda7074)
*Figure 2.1 - Truth Table for part B*

### Circuit
![image](https://github.com/user-attachments/assets/d5c65a23-e50c-4f5c-a738-a26811d2c46f)
*Figure 2.2 - Circuit for part B*

