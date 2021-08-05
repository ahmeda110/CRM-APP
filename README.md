# CRM-APP

Utilized Django, SQLlite3, HTML, CSS, Bootstrap, etc

Status - Complete

# ABOUT
When launched a login page is displayed where users can login/register. Then, depending on the account permissions a user will be redirected to an admin or customer dashboard. Within the admin dashboard, a UI presents the count of total, pending and delivered orders. Admins also have the power to view all customers and products. Moreover, customers can be added/removed, and when clicked on a user their information is readily presented where the admin can update their information; this includes: updating/adding/removing orders, personal information, as well as filtering for a specific order (by name, status, date). On the other hand, the customer dashboard lists their orders along with the status and count of delivered vs pending. Finally, all the above is connected to a SQL database.

# Installing 

On Anaconda Prompt (miniconda3):

1- git clone (https/ssh) depending on your permissions
2- cd CRM-App
3- python manage.py runserver
4- Open your browser and go to 'http://localhost:8000/'

# Extras

If you would like to access the application as an admin, before step 3 do the following:

1- python manage.py createsuperuser
2- fill in username, pass, email. These credentials will be used in the apps login as well as to the database

