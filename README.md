# About The Online Quiz System
> - [Harvard-Cs50 Final Project](https://cs50.harvard.edu/web/2020/)

## Scenarios and objectives for creating an online Quiz project
Creating an online test project aims to increase competition and effort among the students. To be listed on the website, students must constantly read and review their lessons, complete teacher-assigned daily tests, and participate in self-assessments.

## Project features and capabilities
Teachers: The project allows teachers and professors to create daily or weekly competitions and assignments for students by using online multiple-choice tests. 
Students: Students can take these quizzes by creating an account on the website, logging into the user dashboard, and viewing their scores after completing the quiz.
Additionally, the site includes a leaderboard section where users can see the top candidates and their test scores.

## What distinguishes this project from others? (Distinctiveness and Complexity)
Unlike other course projects that focus on Wiki project, Commerce, Mail, and Network, this project focuses on an online QUIZ system. Furthermore, it offers more benefits to students than other projects.

## Reasons for implementation of the project :
1. Reviewing students' lessons and assignments.
2. Evaluating their progress and facilitating the learning of new course materials.
3. Exploring an online testing system.
4. Foster competition and cultivate a positive attitude towards learning.

## Website Features:

### Features of the quiz test:
-	All questions are multiple-choice questions.
-	Each question is displayed only once per user.
-	Questions are displayed randomly for every user.
-	If the user by mistake presses refresh or go back to the previous page, there will be a new question for the user and the question he/she was on will be marked as attempted.
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
__________________________________________________________________________________________________________________
## Description of project files:

```runtime.txt```   --   Python version to running the web program\
```requirements.txt```  --  all requirements to install for program\
```Procfile```   --   This file is used to explicitly declare your application’s process types and entry points.\
```pipfile```   --   Pipfile is the dedicated file used by the Pipenv virtual environment to manage project dependencies. This file is essential for using Pipenv.\
```manage.py```   --   Main file for run project\
```db.sqlite3```   --   Website Database\
```/templates```   --   Static Front-end (HTML)\
```/static```   --   Main CSS and JavaScript Files\
```/QuizApp & /quiz_app```   --   Django CORE directory structure
