# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
NAME : RAJA GOPAL V
REG No : 212223240134
```

```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```
## Line Plot:
```
attendence=[95,80,78,65]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(attendence,student)
 plt.xlabel('Attendance')
 plt.ylabel('Student name')
 plt.show()
```

<img width="719" height="537" alt="image" src="https://github.com/user-attachments/assets/d8d80e7d-6b2e-4c15-93a2-4224f7ee0cc1" />

## Scatter Plot:
```
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='brown')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```

<img width="702" height="565" alt="image" src="https://github.com/user-attachments/assets/8d8df595-2b83-466d-b3b1-ecedc1179dee" />

## Pie Chart:

```
act=['eat','sleep','work']
slices=[2,4,6]
colors = ['r','b','g']
plt.pie(slices,labels=act,colors=colors,startangle=90,shadow=True,explode=(0,0.1,0),autopct='%1.1f%%')

plt.legend()
plt.show()
```
<img width="508" height="484" alt="image" src="https://github.com/user-attachments/assets/87d06b54-ec1a-4971-8969-5e8884122d15" />

## Area Chart:

```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```
<img src="https://github.com/PriyankaAnnadurai/EXNO-5-DS/assets/118351569/c59b9cd9-fd38-425e-97ee-9de8c42674dd" width="300" height="300">

## BAR CHART 

```
import matplotlib.pyplot as plt
x1=[1,2,3,4,5]
y1=[2,6,8,10,16]
plt.xlim(1,6)
plt.ylim(1,20)
c1=['red', 'green'] 
plt.title('My bar chart!')
plt.bar (x1, y1, width=0.8, color=c1)
```

<img width="629" height="488" alt="image" src="https://github.com/user-attachments/assets/a318219f-21e9-4155-a0ba-1236e86c1ff6" />

### Histogram:

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```


<img src="https://github.com/PriyankaAnnadurai/EXNO-5-DS/assets/118351569/5355375e-9777-4bc8-83c1-cae6d2da9c2a" width="300" height="300">


### Box Plot:

```py
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```


<img src="https://github.com/PriyankaAnnadurai/EXNO-5-DS/assets/118351569/6b540f13-933a-4cf4-8923-eeb8642ffbb2" width="300" height="300">


```py
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img src="https://github.com/PriyankaAnnadurai/EXNO-5-DS/assets/118351569/4e6304ff-5a0b-49bd-be9a-45798994d467" width="300" height="300">




# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
