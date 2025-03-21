# Ex02 Django ORM Web Application
## Date: 21-03-2025

## AIM
To develop a Django application to store and retrieve data from a Movies Database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM
![image](https://github.com/user-attachments/assets/ca6c18ac-104f-4bed-9bfd-315fb2ce8f56)



## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM

```python
from django.db import models

class student(models.Model):
    user=models.CharField(max_length=100,primary_key=True)
    password=models.CharField(max_length=100)
    email=models.EmailField()
    phone=models.CharField(max_length=100)
    profile=models.ImageField(upload_to='profile/')
    address=models.TextField()
```



## OUTPUT

![Screenshot 2025-03-21 110312](https://github.com/user-attachments/assets/0bdf6d32-e903-46e4-aeab-7841b8841fe3)



## RESULT
Thus the program for creating movies database using ORM hass been executed successfully
