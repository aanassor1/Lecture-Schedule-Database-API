# Lecture Schedule Database API

### Author
Abdul Aziz Nassor

### Description

A web application that manipulates objects in a database using REST API. 

A database is made that stores the schedules of lecturers and their sessions. The database would then be able to be modified using Java's Spring REST API.

Controllers had to be created to control each of these classes for creation and deletion in the database.

Repositories was also used to give the ability to look for different objects using their id, name etc. and to give lists to the user.

### What I learnt
* How to use REST Api
* Database creation
* Controllers
* Object Manipulation
* Repositories
  
### Installation

Go onto Github, find the project and clone the repository.
Afterwards, open bash, locate the destinated file with 'cd', and use git clone on the cloned repository.

```bash
git clone https://github.com/aanassor1/Lecture-Schedule-Database-API.git
```

After, create a java product on an IDE that allows packages. Then create a package for each folder (domain, controller, repo) and then put in the respective children in each of those folders. Put the resources folder, ErrorInfo.class and Part1Application in the main project folder.

Access the application.resources folder and change the datasource url, username, and password to your database settings.

Then, run the Part1Application file and on your website, open up the website - http://localhost:8080/.
