# Online Quiz System Project
> - [Harvard-Cs50w Final Project](https://cs50.harvard.edu/web/2020/)

#### Video Demo: https://youtu.be/V7lro9pbKKA?si=AKzpITa0QSjqWNh-

# Purpose of the project:
This is my final project for The Harvard CS50 Web course.
Creating an online Quiz project aims to increase competition and effort among the students. To be listed on the website, students must constantly read and review their lessons, complete teacher-assigned daily tests, and participate in self-assessments.

# Distinctiveness and Complexity:
Distinctiveness of this project Unlike other course projects focusing on Wiki projects, Commerce, Mail, and Network, this project focuses on an online QUIZ system. Furthermore, it offers more benefits to students than other projects, and This project helps students to measure their skills compared to their other friends and review their lessons, The complexity of this project is to display questions randomly for each user and Each question once displayed for users, and the users can see grade results after the quiz, These were the three challenges and complications that I faced during the construction of the project and implemented it.
__________________________________________________________________________________________________________________________
## Website Features:

### quiz test Features:
-   All questions are multiple-choice questions.
-   Each question is displayed only once per user.
-   Questions are displayed randomly for every user.
-   If the user by mistake presses refresh or go back to the previous page, there will be a new question for the user and the question he/she was on will be marked as attempted.
-   A message will be displayed after every attempted question whether the answer is correct or incorrect.

### Leaderboard features:
-   Leaderboard is a short list according to the score obtained by the users.
-   If two users have the same score, the user who has signed up earlier will have a better ranking than the one who joined late.
-   Leaderboard is open to all.

### Admin features:
-   Only the admin can add questions.
-   Admin can add questions and modify them until they are not marked as Has been published?
-   Once a question has been published, it can neither be modified nor can be accessed. Admin can only see a list of questions.
-   Admin can search questions by question text or choice text.
-   Admin can filter questions based on whether the questions have been published or not.
__________________________________________________________________________________________________________________________
## Technologies used : 
HTML – CSS || JavaScript || Bootstrap4 (Mobile Responsive) || Python - Django framework
__________________________________________________________________________________________________________________________
## How to Run the Program:
1.  cd quiz application directory
2.  pip install pipenv
3.  pipenv shell
4.  pip install -r requirements.txt
5.  python manage.py migrate
6.  python manage.py createsuperuser
7.  python manage.py runserver
__________________________________________________________________________________________________________________________
## Files and directories:

#### quiz_app directory
- ```/quiz_app/__init__.py ```                            --     Python file that is used to indicate that the directory it is present in is a Python package
- ```/quiz_app/admin.py ```                               --     this file is used for registering the models into the Django administration. The models that are present have a superuser/admin who can control the information that is being stored.
- ```/quiz_app/apps.py ```                                --     This file deals with the application configuration of the apps. The default configuration is sufficient enough in most of the cases
- ```/quiz_app/forms.py ```                               --     where the Django documentation places all forms of code; to keep your code easily maintainable 
- ```/quiz_app/models.py ```                              --     ORM profile model. Contains a Profile class which has all the information of a user
- ```/quiz_app/tests.py ```                               --     Django uses the unit test module's built-in test discovery, which will discover tests under the current working directory in any file named
- ```/quiz_app/urls.py ```                                --     prep-defined path for the admin app. However, Django recommends mapping all resources via another This file is newly created under the app
- ```/quiz_app/views.py ```                               --     Contains all view functions for profile, like view, edit, and delete profile as well as change password

#### QuizApp directory
- ```/QuizApp/__init__.py```                              --     Python file that is used to indicate that the directory it is present in is a Python package
- ```/QuizApp/asgi.py```                                  --     ASGI provides an interface between asynchronous Python web servers and frameworks
- ```/QuizApp/settings.py```                              --     Application CORE settings
- ```/QuizApp/urls.py```                                  --     all application URLs
- ```/QuizApp/wsgi.py```                                  --     mediator that communicates between web servers and Python web applications

#### static directory
- ```/static/css/main.css```                              --     Main CSS File
- ```/static/js/main.js```                                --     Main JavaScript File

#### templates directory
- ```/templates/admin/base_site.html```                   --     template Base Admin page
- ```/templates/quiz/error_404.html & error_500.html```   --     template Error Page
- ```/templates/quiz/home.html```                         --     template main Global page
- ```/templates/quiz/leaderboard.html```                  --     template Leaderboard for Show-Score of student
- ```/templates/quiz/login.html```                        --     template login page
- ```/templates/quiz/play.html```                         --     template page for start and play quiz
- ```/templates/quiz/registration.html```                 --     template page for registration User
- ```/templates/quiz/submission_result.html```            --     submit Result of Quiz
- ```/templates/quiz/user_home.html```                    --     template home page for Website Users
- ```/templates/base.html```                              --     base HTML structure

#### main root directory
- ```db.sqlite3```                                        --     Website Database
- ```manage.py```                                         --     Main file for run project
- ```Pipfile```                                           --     dedicated file used by the Pipenv virtual environment to manage project dependencies
- ```Procfile```                                          --     Procfile lists the process types in an application
- ```requirements.txt```                                  --     all requirements to install for program
- ```runtime.txt```                                       --     Python version to running the web program
