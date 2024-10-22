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
### Developed by:
```python
Name: NARAMALA KUMARTEJA
Reg No: 212223230132
```
# Coding and Output:
```python
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![image](https://github.com/user-attachments/assets/201ebd7c-6696-4d5e-980d-b9744d50b89e)
```python
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph')
plt.show()
```
![image](https://github.com/user-attachments/assets/a71fe14e-5b0c-4ff1-9475-a2438cbb071f)
```python
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line 1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.title("Two Lines On Same Graph")
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/3e6f5fac-8bad-4975-92b1-11fb936a11ef)
```python
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlim(1,8)
plt.ylim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```
![image](https://github.com/user-attachments/assets/58cc461f-06d9-46d1-9c1c-3bd53e4ae911)
```python
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![image](https://github.com/user-attachments/assets/f18043cb-9776-4761-9081-7f708d1d7a5d)
```python
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![image](https://github.com/user-attachments/assets/e22fb67d-c363-4d4f-8f36-469451d66d79)
```python
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
```
![image](https://github.com/user-attachments/assets/5dabfdfd-57eb-442f-b33b-bf40ce35b944)
```python
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.title("Crop Yield in Kanto")
plt.legend(['Apples','Oranges'])
```
![image](https://github.com/user-attachments/assets/2c9231e9-38b6-42ff-8dd1-ac97d969f594)
```python
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
```
![image](https://github.com/user-attachments/assets/e593fa81-41f2-46fd-9c28-74f95f443b8c)
```python
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)")
```
![image](https://github.com/user-attachments/assets/e937d056-6a1f-4958-832b-ebb8615aa399)
```python
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare')
plt.title("Crop Yield in Kanto")
plt.legend(['Apples','Oranges'])
```
![image](https://github.com/user-attachments/assets/c890caeb-2bf5-4d63-a27c-1a9db0754797)
```python
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![image](https://github.com/user-attachments/assets/2b4511ca-cacb-488c-a733-c0f0f0794611)
```python
x=[1,2,3,4,5,6,7,8,9,10]
y=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x,y,label="stars",color="green",marker="*",s=30)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/1c6c0ef1-cb56-470d-b2dc-b41e09dfb0f1)
```python
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
```
```python
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![image](https://github.com/user-attachments/assets/3bda90d0-622a-4643-a69a-0d50a34a8a03)
```python
y
```
![image](https://github.com/user-attachments/assets/ec3936af-8144-42c8-b4f5-7d1e2ef1aad4)
```python
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/user-attachments/assets/032627ad-0863-456c-96e8-4d05323be4e9)
```python
x=np.arange(0,10)
y=x*x
y
```
![image](https://github.com/user-attachments/assets/9793346c-746a-4aff-babd-f4f192934ef3)
```python
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('2D Diaram')
```
![image](https://github.com/user-attachments/assets/a600c14a-e24b-411e-89f6-fce6f4fe009a)
```python
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
```
![image](https://github.com/user-attachments/assets/7dcfe6fa-b3fc-4a7b-8ede-cfcc2bc7c891)
```python
np.pi
```
![image-19](https://github.com/user-attachments/assets/2275cc40-194a-41dd-9c69-c75630aa8ea0)
```python
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("Sine Wave Form")
plt.plot(x,y)
plt.show()
```
![image](https://github.com/user-attachments/assets/cca2d08a-4256-4682-bdb0-9584398de2b0)
```python
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/user-attachments/assets/a8144715-c0d5-48b4-b71e-7571b2297200)
```python
plt.stackplot(x,y1,y2,y3,labels=['Line 1','Line 2','Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/fe73a032-da09-4d48-a5ca-c71cdaf70841)
```python
x=np.array([1,2,3,4,5,6,7,8,9,10])
y=np.array([2,4,5,7,8,8,9,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='spline')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/85a34fcb-b22f-47cf-a946-dd58d34ccdb5)
```python
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="green")
plt.show()
```
![image](https://github.com/user-attachments/assets/f96d8dd1-baaf-49ec-9b76-00fc88e724d3)
```python
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="yellowgreen")
plt.show()
```
![image](https://github.com/user-attachments/assets/4d671b38-6b3b-419f-ab3b-51be5b2c1d77)
```python
heigth=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,heigth,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart')
plt.show()
```
![image](https://github.com/user-attachments/assets/5ef30afc-d5b5-4b75-a0bb-417fe0dcdef1)
```python
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/c7d1a492-3e3d-4e36-bafc-591ebf14e45b)
```python
age=[2,5,70,30,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(age,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.of people')
plt.title('My histogram')
plt.show()
```
![image](https://github.com/user-attachments/assets/b6c278d5-a446-4404-82ae-e99d25a7b3e9)
```python
x=[2,1,6,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```
![image](https://github.com/user-attachments/assets/5fad2069-2cd8-4d3d-9981-d4539e2cff02)
```python
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/user-attachments/assets/eee38506-734d-48d5-ab00-314af65a26a2)
```python
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('values')
ax.set_title('Box Plot')
```
![image](https://github.com/user-attachments/assets/507340c7-4172-4e5c-9ddf-dc14cd83afc2)
```python
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/7458f935-9f1c-4768-b1a6-88dd7181d3c5)
```python
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/ca2ed0af-8a2f-45cd-8d1d-5f6688ae1e14)
# Result:
The Execution Data Visualization is done successfully.
