## Building Web Applications

### For Context

This week, we will be grouped based on our Pod (POD A and POD B) to complete two different projects. They are:

1. Hotel Management System (HMS) --> (POD A)

A project description, features to implement and approach to follow are in `POD_A.md`  file respectively at the root of this project.

<!-- At this point you are expect to checkout `POD_A.md` or `POD_B.md` file depending on your POD. -->

Happy Hacking ...

This project is about a hotel management system which have four users, this include a customer, receptionist , admin/manager and a super admin.The customer can login/signup,book a room and make payment .The receptionist can take payment and book room for customers. the admin creates account for the receptionist and delete  the account for the receptionist if needed. the super admin can create account for the super admin, receptionist as well as delete their accounts if needs be

To start this task we run our project with 

==> actiavte our environment {python3 -m venv venv,source venv/bin/activate, }
==> install the frame work {python -m pip install django}
==> Run the project django-django admin startproject (name of project)
==> start your app {python manage.py startapp users}
==> add yout appp to the installed app @ the settings
==> apply migration and runserver {python manage.py migrate, python manage.py runserver}
==> 
