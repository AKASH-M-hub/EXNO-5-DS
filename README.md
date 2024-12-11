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
from google.colab import drive

drive.mount('/content/drive')

![image](https://github.com/user-attachments/assets/6f5057dd-3a57-4eaf-9c13-8a35730bb57d)

import matplotlib.pyplot as plt

x_values=[0,1,2,3,4,5]

y_values=[0,1,4,9,16,25]

plt.plot(x_values,y_values)

![image](https://github.com/user-attachments/assets/f3ca1c7c-9911-48ee-9edb-51cfc8944952)

plt.show()

x=[1,2,3,4]

y=[2,4,6,8]

plt.plot(x,y)

![image](https://github.com/user-attachments/assets/9e1a5a57-253d-424d-bffb-129cf7ac1fe1)

plt.xlabel("x-axis")

plt.ylabel("y-axis")

plt.title("first graph")

plt.plot(x,y)

plt.show()

![image](https://github.com/user-attachments/assets/6c22b69a-0c70-47c9-9de4-f29e44d973b2)

x1=[1,2,3,4]

y1=[2,4,6,8]

x2=[3,5,7,8]

y2=[4,6,7,8]

plt.plot(x1,y1,label="line 1")

plt.plot(x2,y2,label="line 2")

plt.xlabel("x-axis")

plt.ylabel("y-axis")

plt.title("two lines on same graph")

plt.legend()

plt.show()

![image](https://github.com/user-attachments/assets/a913cc9b-6ef4-406d-a3e7-b66dc35dfff0)

plt.xlabel("x-axis")

plt.ylabel("y-axis")

plt.title("two lines on same graph")

plt.legend()

plt.show()

x=[1,2,3,4]

y=[2,4,6,8]

plt.plot(x,y,color="green",linestyle="dashed",linewidth=3,marker='o',markerfacecolor="blue",markersize=12)

![image](https://github.com/user-attachments/assets/fa9efcc9-5b4b-40c7-b09d-1043ea3a2ea4)

yield_apples=[0.345,0.765,0.876,0.898]

plt.plot(yield_apples)

![image](https://github.com/user-attachments/assets/be27cf11-6b23-49e0-b4e2-28726f71f16c)

years=[2010,2015,2020,2025]

yield_apples=[0.345,0.765,0.876,0.898]

plt.plot(years,yield_apples)

![image](https://github.com/user-attachments/assets/966f829e-3507-4c62-97a8-1908e780d495)

years=range(2000,2012)

apples=[0.455,0.563,0.356,0.536]

oranges=[0.242,0.344,0.244,0.324]

plt.plot(years)

![image](https://github.com/user-attachments/assets/f1530972-9591-48b2-b95a-dfbde2ba0f0a)

years=[2000,2005,2010,2015,2020]

yield_apples=[0.434,0.232,0.323,0.323,0.323]

plt.plot(years,yield_apples)

plt.xlabel('year')

plt.ylabel("yield([pertons])")

![image](https://github.com/user-attachments/assets/50e5729b-2d93-43d0-98a7-e1bd9fb960b4)

plt.figure(figsize=(12,6))

years=[2000,2005,2010,2015,2020]

apples=[0.243,0.234,0.213,0.341,0.312]

plt.plot(years,apples,marker='o')

![image](https://github.com/user-attachments/assets/ec57be51-f7dc-4e51-8403-b9d123773a22)

years=[2000,2005,2010,2015]

apples=[0.34,0.342,0.45,0.34]

oranges=[0.234,0.121,0.9878,0.973]

plt.plot(years,apples,marker='o')

plt.plot(years,oranges,marker='x')

plt.xlabel("year")

plt.ylabel("yields[tons per hectare]")

plt.title("crops yields in kanto")

plt.legend(apples,oranges)

![image](https://github.com/user-attachments/assets/1ac06177-594d-432c-a459-60e954a597bf)

import matplotlib.pyplot as plt

x_values=[1,2,3,4]

y_values=[0,3,1,2]

plt.scatter(x_values,y_values,s=30,color="blue")

![image](https://github.com/user-attachments/assets/2080d9ff-b8df-4eec-897e-97a18ec3e7f1)

import numpy as np

import pandas as pd

x=np.arange(0,10)

y=np.arange(11,21)

x

![image](https://github.com/user-attachments/assets/2efa2520-38b1-4f3d-876d-28b819fc6c6c)

y

![image](https://github.com/user-attachments/assets/397a7086-8034-471b-bf15-6bc30118b823)

plt.scatter(x,y,c='r')

plt.xlabel("X axis")

plt.ylabel("Y axis")

plt.title("graph in 2D")

plt.savefig("Test.png")

![image](https://github.com/user-attachments/assets/9c7c8483-25e8-4713-b320-b54f70902401)

y=x*x

y

![image](https://github.com/user-attachments/assets/20c7631d-de9b-41d1-af8e-aa6592385d9c)

plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)

plt.xlabel("X-axis")

plt.ylabel("Y-axis")

plt.title("2-D diagram")

![image](https://github.com/user-attachments/assets/12a08fde-7f22-4852-8835-dc2af056c5f8)

plt.subplot(2,2,1)

plt.plot(x,y,'r--')

plt.subplot(2,2,2)

plt.plot(x,y,'g*--')

plt.subplot(2,2,3)

plt.plot(x,y,'bo')

plt.subplot(2,2,4)

plt.plot(x,y,'go')

![image](https://github.com/user-attachments/assets/1dcf6993-d08c-46e1-8114-7b8fcaccf670)

np.pi

![image](https://github.com/user-attachments/assets/a8253b7d-3e04-4878-a197-f7330131f36c)

x=np.arange(0,4*np.pi,0.1)

y=np.sin(x)

plt.title("sine wave form")

plt.plot(x,y)

plt.show()

![image](https://github.com/user-attachments/assets/d01ddd84-e059-452f-883e-b39e66d7bb4f)

import matplotlib.pyplot as plt

import numpy as np

x=[1,2,3,4]

y1=[2,4,6,8]

y2=[5,7,9,7]

y3=[1,2,4,6]

plt.fill_between(x,y1,color='blue')

plt.fill_between(x,y2,color='green')

plt.plot(x,y1,color='red')

plt.plot(x,y2,color='black')

plt.legend(['y1','y2'])

plt.show()

![image](https://github.com/user-attachments/assets/6e463613-7f7e-4a80-a983-cf837ab27813)

plt.stackplot(x,y1,y2,y3,labels=['line1','line2','line3'])

plt.legend(loc='upper left')

plt.title('Stacked line chart')

plt.xlabel('X-Axis')

plt.ylabel('Y-Axis')

plt.show()

import numpy as np

import matplotlib.pyplot as plt

from scipy.interpolate import make_interp_spline

x=np.array([1,2,3,4,5,6,7,8,9])

y=np.array([2,4,5,7,8,9,2,3,3])

spl=make_interp_spline(x,y)

x_smooth=np.linspace(x.min(),x.max(),100)

y_smooth=spl(x_smooth)

plt.plot(x,y,'o',label='data')

plt.plot(x_smooth,y_smooth,'-',label='spline')

plt.legend()

plt.show()

![image](https://github.com/user-attachments/assets/7ea0b626-2a50-48dc-94c2-5fbd28fa4105)

b m[hggcdgdc](url)














































# Result:
 Include your result here
