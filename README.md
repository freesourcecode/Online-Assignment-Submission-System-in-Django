# Online Assignment Submission System in Django Source Code

An **Online Assignment Submission System Project in Django** is a system that allows students to upload their assignments or projects online instead of sending them in a module file.

The proposed method aids teachers in the process of monitoring and handling students by eliminating and mitigating human error.

This is a role-based module in which the teachers and student can perform any operation on the data.

The **Online Assignment Submission System** is an easy project for beginners to learn how to build a web-based python Django project.

>[!NOTE]
> To start creating an **Online Assignment Submission System Project in Python Django**, makes sure that you have PyCharm Professional IDE Installed in your computer.

## Student Features of Online Assignment Submission System Project in Django

* **Manage Student Profile**

For the student profile, the student update his/her information details.

* **Registration**

For the registration, the student need to register first to create their own account.

* **View Assignment and exam**

For the assignment and exam, the student can view their assignment and exam through this website.

* **Login**

By default the student need to login first to enable to access the system.

* **View Course**

For the course, the student can view all their courses.

## Teachers Features of Online Assignment Submission System Project in Django

* **Manage Teacher Profile**

For the teacher profile, the teacher can update his/her information details.

* **Registration**

For the registration, the teacher need to register first to create their own account.

* **Create Course**

For the add course, the teacher can add and update course information.

* **Login**

By default the teacher need to login first to enable to access the system.

* **Create Exam**

For the exam, the teacher can create and update exam information.

* **Create Assignment**

For the assignment, the teacher can create and update assignment information.

## How to Create an Online Assignment Submission System in Django?

Here are the steps on **how to create a Online Assignment Submission System project in Django**.

1 .**Open file**.

First, open “pycharm professional” after that click “file” and click “new project”.

![image](https://github.com/user-attachments/assets/3ee660ed-28e5-4c08-9b36-94b149fb1b2c)

2. **Choose Django**.

Next, after click “new project”, choose “Django” and click.

3. **Select file location**.

Then, select a file location wherever you want.

4. **Create application name.**

After that, name your application.

5. **Click create.**

Lastly, finish creating project by clicking “create” button.

6. **Start Coding.**

Finally, we will now start adding functionality to our Django Framework by adding some functional codes.

## Functionality and Codes of the Online Assignment Submission System Project in Django

* **Create template for the student login in form**

In this section, we will learn on how create a templates for the student login form. 

To begin with, add the following code in your login.html under the folder of templates/authentication/.

```
{% extends 'base.html' %}
{% load bootstrap %}

{% block title %} Login {% endblock %}

{% block content %}

<div class="container">

<div class="row justify-content-center"  style="display: flex!important">

                <div class="col-lg-5 mb-5 mb-lg-0">
                    <center> <h3>Login</h3></center>

                    <form action="" method="POST">{% csrf_token %}

                        {{ form|bootstrap }}

                        <div class="row form-group">
                            <div class="col-md-12">
                                <input type="submit" value="Login" class="btn btn-primary btn-md text-white">
                            </div>
                        </div>


                    </form>
                </div>

            </div>
        </div>

{% endblock %}
```
* **Create template for the student registration**

In this section, we will learn on how create a templates for the student registration. 

To start with, add the following code in your register.html under the folder of templates/authentication/student.

```
{% extends 'base.html' %}
{% load bootstrap %}

{% block title %} Student Registration {% endblock %}

{% block content %}



<div class="container">

<div class="row justify-content-center" style="display: flex!important" >

                <div class="col-lg-5 mb-5 mb-lg-0" >

                 <center><h3>Student Registration</h3> </center>
                    <form action="" method="POST">{% csrf_token %}

                        {{ form|bootstrap }}

                        <div class="row form-group">
                            <div class="col-md-12">
                                <input type="submit" value="Register" class="btn btn-primary btn-md text-white">
                            </div>
                        </div>


                    </form>
                </div>

            </div>
        </div>

{% endblock %}

```

* **Create template for the create assignment form**

In this section, we will learn on how create a templates for the create assignment form.

To start with, add the following code in your assignment_create.html under the folder of templates/core/instructor.

```
{% extends 'base.html' %}

{% load bootstrap %}

{% block title %} Course Create {% endblock %}

{% block content %}

    <section class="dentist-area section-padding-40-0">
<div class="container">

<div class="row justify-content-center">

                <div class="col-lg-5 mb-5 mb-lg-0">
                    <center> <h3>Create Course</h3></center>

                    <form action="" method="POST" enctype="multipart/form-data">{% csrf_token %}

                        {{ form|bootstrap }}

                        <div class="row form-group">
                            <div class="col-md-12">
                                <input type="submit" value="Create" class="btn btn-primary btn-md text-white">
                            </div>
                        </div>

                    </form>
                </div>

            </div>
        </div>
    </section>

{% endblock %}
```
### 📌Here's the full documentation for the [Online Assignment Submission System in Django](https://itsourcecode.com/free-projects/python-projects/online-assignment-submission-system-in-django-with-source-code/)

