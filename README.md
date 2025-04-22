# Ex02 Django ORM Web Application
# Date: 22/04/2025
# AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).

# ENTITY RELATIONSHIP DIAGRAM
## DESIGN STEPS
## STEP 1:
Clone the problem from GitHub

## STEP 2:
Create a new app in Django project

## STEP 3:
Enter the code for admin.py and models.py

## STEP 4:
Execute Django admin and create details for 10 books

# PROGRAM
    from django.db import models                                                                                                                                                                                          
    from django.contrib import admin                                                                                                                                                                                      
    class footballplayer (models.Model):                                                                                                                                                                                
    
        name=models.CharField(max_length=20)                                                                                                                                                                              
        weight=models.IntegerField()                                                                                                                                                                                      
        players_id=models.CharField(max_length=100)                                                                                                                                                                       
        age=models.IntegerField()                                                                                                                                                                                         
        members=models.CharField(max_length=20)

    class footballplayerAdmin(admin.ModelAdmin):                                                                                                                                                                         
    
        list_display=('name','players_id','weight','age','members')

    admin.py

        from django.contrib import admin                                                                                                                                                                                         
        from django.contrib import admin                                                                                                                                                                                                   
        admin.site.register(footballplayer,footballplayerAdmin)



# OUTPUT

![image](https://github.com/user-attachments/assets/2f37dddd-539c-4843-8d45-0fce815dfcf2)


# RESULT
Thus the program for creating a database using ORM hass been executed successfully
