# HarvardX CS50W: Web Programming with Python and JavaScript
> - [Harvard-Cs50 Final Project](https://cs50.harvard.edu/web/2020/)

## PURPOSE OF THE PROJECT:
This is my final project for Harvard CS50x course.
Creating an online test project aims to increase competition and effort among the students. To be listed on the website, students must constantly read and review their lessons, complete teacher-assigned daily tests, and participate in self-assessments.

## Distinctiveness and Complexity:
Unlike other course projects that focus on Wiki project, Commerce, Mail, and Network, this project focuses on an online QUIZ system. Furthermore, it offers more benefits to students than other projects, and This project helps students to measure their skills compared to their other friends and review their lessons.
__________________________________________________________________________________________________________________________
## Website Features:

### Features of the quiz test:
-	All questions are multiple-choice questions.
-	Each question is displayed only once per user.
-	Questions are displayed randomly for every user.
-	If the user by mistake presses refresh or go back to the previous page, there will be a new question for the user and the question he/she was on will be marked as   attempted.
-	A message will be displayed after every attempted question whether the answer was correct or incorrect.

### Leaderboard features:
-	Leaderboard is a short list according to the score obtained by the users.
-	If two users are having the same score, the user who has signed up earlier will have good ranking than the one who joined late.
-	Leaderboard is open to all.

### Admin features:
-	Only the admin can add questions.
-	Admin can add questions and modify them until they are not marked as Has been published?
-	Once a question has been published, it can neither be modified nor can be accessed. Admin can only see a list of questions.
-	Admin can search questions by question text or choice text.
-	Admin can filter questions based on whether the questions have been published or not.
__________________________________________________________________________________________________________________________
## Technologies used : 
HTML – CSS || JavaScript || Bootstrap4 (Mobile Responsive) || Python - Django framework
__________________________________________________________________________________________________________________________
## How to Run the Program:
1.	cd quiz application directory
2.	pip install pipenv
3.	pipenv shell
4.	pip install -r requirements.txt
5.	python manage.py migrate
6.	python manage.py createsuperuser
7.	python manage.py runserver
__________________________________________________________________________________________________________________________
## Files and directories:

```/templates/base.html```   --   base HTML structure\
```/templates/quiz/error_404.html & error_500.html```   --   template Error Page\
```/templates/quiz/home.html```   --   template main Global page\
```/templates/quiz/leaderboard.html```   --   template Leaderboard for Show Score of student\
```/templates/quiz/login.html```   --  template login page\
```/templates/quiz/play.html```   --   template page for start and play quiz\
```/templates/quiz/registration.html```   --   template page for registration User\
```/templates/quiz/submission_result.html```   --   submit Result of Quiz\
```/templates/quiz/user_home.html```   --   template home page for Website Users\
```/templates/admin/base_site.html```   --   template Base Admin page\
```/static/css/main.css```   --   Main CSS File\
```/static/js/main.js```   --   Main javaScript File\
```/QuizApp/urls.py```   --   all application URLs\
```/QuizApp/settings.py```   --   Application CORE settings\
```requirements.txt```  --  all requirements to install for program\
```manage.py```   --   Main file for run project\
```db.sqlite3```   --   Website Database\
```runtime.txt```   --   Python version to running the web program\
