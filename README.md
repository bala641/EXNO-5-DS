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
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
x = [1, 2, 3, 4, 5]
y = [3, 6, 2, 7, 1]
plt.plot(x,y,label='line1')

```
## output

![image](https://github.com/user-attachments/assets/f87ed991-97eb-4183-bc13-981c7d6fa1c8)

```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
x1 = [1,2,3]
y1 = [2,4,1]
x2 = [1,2,3]
y2 = [4,1,3]

plt.plot(x1, y1, label='line1')
plt.plot(x2, y2, label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()

```
## output
![image](https://github.com/user-attachments/assets/9ff41f94-d2a8-4723-ba4e-6670ee103e76)

```
 import matplotlib.pyplot as plt
 x=[1,2,3,4,5,6]
 y=[2,4,1,5,2,6]
 plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
 plt.xlabel('x-axis')
 plt.ylabel('y-axis')
 plt.title('Some cool customizations!')
 plt.show()

```
## output
![image](https://github.com/user-attachments/assets/a17b886a-cacc-4054-a882-e4c63534a018)

```
 yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
 plt.plot(yield_apples)
```
## output
![image](https://github.com/user-attachments/assets/04083ae5-cb13-4aa4-a108-ace28d98985c)

```
 years=[2010,2011,2012,2013,2014,2015]
 yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
 plt.plot(years,yield_apples)
```
## output
![image](https://github.com/user-attachments/assets/10bf4c99-95d6-4a83-9678-a03cc50341f4)

```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);

```
## output
![image](https://github.com/user-attachments/assets/bfdaf189-ae4c-4886-be2f-61af356efd78)

```
 plt.figure(figsize=(12,6))
 plt.plot(years,oranges,marker='o')
 plt.title("Yield of Oranges (tons per hectare)");
```
![download](https://github.com/user-attachments/assets/8401c090-1099-4b20-87e3-e3cbb09abc5c)
```
 import matplotlib.pyplot as plt
 import numpy as np
 import pandas as pd
 x=np.arange(0,10)
 y=np.arange(11,21)
 x
```
## output
![image](https://github.com/user-attachments/assets/12255e49-8052-4988-88e5-e2a2a9143cb4)
```
 import matplotlib.pyplot as plt
 import numpy as np
 import pandas as pd
 x=np.arange(0,10)
 y=np.arange(11,21)
 y
```
## output
![image](https://github.com/user-attachments/assets/c4a38d10-17af-4ffc-964c-ea0e89c5aef3)

```
plt.scatter(x,y,c='r')
 plt.xlabel('X-axis')
 plt.ylabel('Y-axis')
 plt.title('Graph in 2D')
 plt.savefig('Test.png')
```
## output
![download](https://github.com/user-attachments/assets/cf6d2021-53d9-4c6d-8054-d937cd75d6cc)


```
 y=x*x
 y
```
## output
![image](https://github.com/user-attachments/assets/d9c516bf-6890-428a-9737-c4fd1c41b613)
```
 plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
 plt.xlabel('X axis')
 plt.ylabel('Y axis')
 plt.title('2d Diagram')
 plt.legend(['y-values']);
```
## output
![download](https://github.com/user-attachments/assets/191c9873-fd3e-4273-91c2-099eb9bb3341)
```
 x=np.arange(0,4*np.pi,0.1)
 y=np.sin(x)
 plt.title("sine wave form")
 plt.plot(x,y)
 plt.show()
```
## output

![download](https://github.com/user-attachments/assets/5bd6e6d2-1c16-4920-97f3-b8087d4fcf71)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')

```
## output
![download](https://github.com/user-attachments/assets/c637e512-f435-4fb2-9ce2-0fd36b9c3f5d)
```
import matplotlib.pyplot as plt
 import numpy as np
 x=[1,2,3,4,5]
 y1=[10,12,14,16,18]
 y2=[5,7,9,11,13]
 y3=[2,4,6,8,10]
 plt.fill_between(x,y1,color='blue')
 plt.fill_between(x,y2,color='green')
 plt.plot(x,y1,color='red')
 plt.plot(x,y2,color='black')
 plt.legend(['y1','y2'])
 plt.show()

```
## output
![download](https://github.com/user-attachments/assets/0693df59-7d7e-49c4-9c41-9b0e61533a26)
```
 import matplotlib.pyplot as plt
 height=[10,24,36,40,5]
 names=['one','two','three','four','five']
 c1=['red','green']
 c2=['b','g']
 plt.bar(names,height,width=0.8,color=c1)
 plt.xlabel('x-axis')
 plt.ylabel('y-axis')
 plt.title('My bar chart!')
 plt.show()
```
## output
![download](https://github.com/user-attachments/assets/861bc696-c431-42bb-acd7-02a00277eeed)
```
 x=[2,8,10]
 y=[11,16,9]
 x2=[3,9,11]
 y2=[6,15,7]
 plt.bar(x,y,color='r')
 plt.bar(x2,y2,color='g')
 plt.title('Bar graph')
 plt.ylabel('Y axis')
 plt.xlabel('X axis')
 plt.show()
```
## output
![download](https://github.com/user-attachments/assets/6d57efe0-f6ab-441c-a670-ea92b68af820)
```
 import matplotlib.pyplot as plt
 ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
 range=(0,100)
 bins=10
 plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
 plt.xlabel('age')
 plt.ylabel('No. of people')
 plt.title('My histogram')
 plt.show()
```
## output
![download](https://github.com/user-attachments/assets/fb86f92f-c8b1-484c-97ef-8f733edc774c)

```
 import matplotlib.pyplot as plt
 import numpy as np
 np.random.seed(0)
 data=np.random.normal(loc=0,scale=1,size=100)
 data
```
## output
![image](https://github.com/user-attachments/assets/e6f2170d-ebbf-4435-b293-10039d996e08)

```
 fig,ax=plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```
## output
![download](https://github.com/user-attachments/assets/54ef0838-c8b4-42e3-a13b-b9e5602f550a)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
## output
![download](https://github.com/user-attachments/assets/eae8ddc7-8b42-49b4-8ceb-bfea0ad542e7)

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
## output
![download](https://github.com/user-attachments/assets/a4c4c958-d943-4e90-a99f-1306d332a393)










# Result:
 Include your result here
