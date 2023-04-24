# Todo-List-with-User-Authentication
This is a To Do List App created using django to perform CRUD operation on todo lists with user authentication.

## Installation
we need to first create a virtual environment to run our django app.

```bash
py -m venv virtualenv
```
To activate virtual environment:
```bash
virtualenv\Scripts\activate.bat
```
After activating virtual environment, we need to install django in virtual environment.
```bash
pip install django
```
To deactivate virtual environment:
```bash
deactivate
```
After creation of virtual environment and django installation, just clone the repository inside virtual environment. 

## Usage
Download the Zip file from the repository and unzip it.
After that we need to copy the files inside our virtualenv that we just created.

To run django server:
```bash
python manage.py runserver
```
After running the server, our web app will be successfully run.

## Task List Page
>This is the page where all tasks list is present. Green colored-circle shows that our task is completed and grey shows that tasks are pending. 
>There is a search box and a search page which can be used to seach a task in task list.
>The logout button on the top-right of the page logouts the user and redirect to login page.
>Plus(+) symbol can be used to create a task, cross(x) symbol can be used to delete a task and we can edit the task by clicking on task title.
![home](https://user-images.githubusercontent.com/92152225/234021707-8d6f3b75-2396-4cdd-87d2-6477263081bc.png)

## Login Page
![login](https://user-images.githubusercontent.com/92152225/234022000-a5f9c075-093c-4e91-aea8-44e5cb80bac6.png)

## Register Page
![Register](https://user-images.githubusercontent.com/92152225/234022159-80419dcf-3d72-476b-aa3e-caaccd28a243.png)

## Task Create Page
We can create a task by clicking on plus(+) symbol on Task list page.
![task-create](https://user-images.githubusercontent.com/92152225/234022685-07fe7cd3-9214-4525-99f1-357e5034ae3e.png)

## Task Delete Confirmation Page
We can delete a task by clicking on cross(x) symbol on Task list page.
![del](https://user-images.githubusercontent.com/92152225/234023410-149eb6f2-940b-416e-9fa3-4f64ff0d4881.png)

## Hosting the Web App
Due to few problems, the django app cannot be hosted. But we will try to host in future.
