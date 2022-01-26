# Scripts for hacking school journal
******
Three usefull scripts're made to 'hack' school electronic journal.
* fix_marks - takes student's name as argument and adds 2 points to "bad_marks"
* remove_chastisements - takes student's name as argument and deletes all chastisements
* create_commendation - takes student's name and class. Generates commendation to student from teacher
## Getting started
Just download Scripts.py to root folder with project https://github.com/devmanorg/e-diary
>
Open terminal in the project directory and type:
> python manage.py shell
>
In django shell you should import all functions from scripts.py
>
>from scripts import fix_marks, remove_chastisements, create_commendation
## Start
In django shell type "function" with argument(s):
>fix_marks(<student_name>)
