# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:



### Step 2:



### Step 3:



### Step 4:



### Step 5:



### Step 6:

Publish the website in the given URL.

## PROGRAM :

```python
from django.contrib import admin
from django.urls import path
from myapp import views

urlpatterns = [
    path('admin/', admin.site.urls),
    path('areaofrectangle/',views.rectarea,name="areaofrectangle"),
    path('',views.rectarea,name="areaofrectangleroot")
]
```


## OUTPUT:

![Area of Rectangle](/images/ex5-output1.jpg)

### Home Page:


## Result:

