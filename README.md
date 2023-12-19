# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:

### STEP 2:

### STEP 3:

Write your own steps

## PROGRAM
models.py
from django.db import models
from django.contrib import admin
# Create your models here.
class Student (models.Model):
referencenumber=models.CharField(max_length=20,help_text="reference
number")
 name=models.CharField(max_length=100)
 age=models.IntegerField()
 email=models.EmailField()
 mobileno=models.IntegerField()
class StudentAdmin(admin.ModelAdmin):
 list_display=
('referencenumber','name','age','email','mobileno')
 admin.py
 from django.contrib import admin
from .models import Student, StudentAdmin
# Register your mo

## OUTPUT![image](https://github.com/vijayashreeb/django-orm-app/assets/147474814/b3e0e300-5fe7-4e7d-9d22-fa579a905690)


Include the screenshot of your admin page.


## RESULT
The program for creating a database using ORM has been executed sucessfully
