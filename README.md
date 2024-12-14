# Ex02 Django ORM Web Application
## Date: 

## AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM
![WhatsApp Image 2024-12-14 at 10 02 37 AM](https://github.com/user-attachments/assets/37031a97-bace-4913-b2b5-c77d41ac0859)



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
''' admin.py

class shad(admin.ModelAdmin); list_display = ('loan_id','loan_amt','cust_acno','cust_name') ''' ''' models.py class bankloan(models.Model); loan_id = models.IntegerField(primary_key=True) loan_type = models.Charfield(max_length=10) loan_amt = models.IntegerField cust_acno = models.IntegerField cust_name = models.CharField(max_length=50) '''


## OUTPUT
![WhatsApp Image 2024-12-14 at 10 02 37 AM (1)](https://github.com/user-attachments/assets/f62e1442-a8d9-4ca2-b6c5-9eb770e233ca)
![WhatsApp Image 2024-12-14 at 10 02 36 AM (1)](https://github.com/user-attachments/assets/87168d0f-83c7-4b59-96d0-5c943b4ee75d)





## RESULT
Thus the program for creating a database using ORM hass been executed successfully
