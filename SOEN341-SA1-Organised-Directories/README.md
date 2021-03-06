
# SOEN341-SA1
Website Project for SOEN 341 : Team SA1
### Website link:
ec2-52-91-27-143.compute-1.amazonaws.com (note: may be behind current master)

### Team Members:
- Refat Kamal
- Ming Tao Yu
- Jonathan Cournoyer
- Eric Kokmanian
- Aida Bumbu
- Kresten Ordekian
- Jessica Allaire
- Sumit Bharti

### How to run our website locally:
- Install XAMPP (see dev environment for more details)
- In XAMPP, open up one Apache instance + one SQL instance
- Use default XAMPP mysql root password. i.e. no password. 
- Follow instruction in github master repo/APP/PHP_HTML/sql_connector.php to set up the backend server. Use queries in github master repo/SQL_DB/sprint_2_createsql to create tables in XAMPP mysql if they have not been already created.
- Place all files from github master repo/PHP-HTML to your local XAMPP/htdoc/okapi directory (create an okapi directory if it does not exist, okapi is the name of our website)
- Go to any browser: type localhost/okapi to access the home page of the website

### Dev environment:
- Git/Github
- Local: 

1) PHPStorm
    - Refat made an excellent suggestion for PHPStorm. Please download it at: www.jetbrains.com/shop/eform/students
    - Follow the conversation in Slack, testing pending.

2) XAMPP
    - Used for mySQL. 
    - What is XAMPP: XAMPP is a free open source plateform that will turn your pc into a temporary local server capable of compiling PHP code (PHP can only be run on a server). It also provides you with a local mySQL database backend. 

    - Where to Download: https://www.apachefriends.org/download.html
    - How to run php with XAMPP https://www.techwalla.com/articles/how-to-run-a-php-file-in-xampp 
    - How to create a mySQL database with XAMPP: https://www.cloudways.com/blog/connect-mysql-with-php/ (Note that the backend code for our website has already been created. Simply copy past the queries found in the .sql file of our SOEN341 repo and execute it on XAMPP to have local testing sql tables.)
    - Why is it worse than PHPStorm: Because it doesn't come with a developer environment to write code in PHP. It just compiles it. You'll need a separate software listed below in order to write codes. 
 

- Remote cloud (Optional): AWS Elastic Beanstalk Application PHP server + MySQL database*. 
  - Sign up for a 12 month free account and read Issues -> TODO: Setup AWS environment for some useful links. 

- Text editor (Mandatory if using XAMPP, optional if using PHPStorm): Sublime Text 3, notepad++ or anything you feel comfortable writing codes in. It doesn't matter what text editors you use as the "compiler" will always be XAMPP

- Link for Sublime Text : https://www.sublimetext.com/

*Note that AWS is optional. You can start developing with just XAMPP + text editor + Git & not everyone needs to have an AWS account. I however recommend looking into AWS if cloud computing interests you. 


### Main languages: 
PHP, SQL (alternative to PHP to be discussed, i.e. javascript + node.js) 
Front end: HTML, CSS, Javascript, bootstrap, 

- PHP Tutorial CodeAcademy : https://www.codecademy.com/en/tracks/php

- SQL Tutorial CodeAcademy : https://www.codecademy.com/catalog/language/sql

- HTML & CSS - CodeAcademy : https://www.codecademy.com/catalog/language/html-css

- Javascript - CodeAcademy : https://www.codecademy.com/catalog/language/javascript

### Sprint 1 objectives:

Please see issue tab for comprehensive list

SUMMARY - All team members needs to:
- Clone the master repo, create a new branch, attempt to add your name to the "Team Members" list in the readme of the master branch from the new branch you created through a git "Pull Request" (please feel free to message on slack if you need help for this step). You should then review someone else's pull request and approve it. 
- Setup dev environment with the softwares mentionned above
- Look into the "issue" section of the repo 
- Look into Sprint 2 objective since half of sprint 2 is during midterm week. We'll start working on sprint 2 right away. 
- Complete the task assigned in the "issue" section of the repo. The task are design to help you familiarize with the dev environment and to start working on the basic architecture of our website.

### Sprint 2 objectives:
- Read this tutorial: https://code.tutsplus.com/tutorials/how-to-create-a-phpmysql-powered-forum-from-scratch--net-10188
- Complete the basic backbone of the Stackoverflow-like website before the 10th of December (Deadline is the 14th. However, this coincide with midterm week and should be avoided) 

### Formatting for branch and issue names
- For this, we will try to set up a neat formatting strategy to help us organise the project in a smart way.

    - Formatting for name: 
    - SA1 #[issue number] : [Title of Issue]

    - Formatting for description : 
    - Author: [Author of issue]

    - Description : [Description of what shall be fixed]

- The issue number will be the main identifiers of issues and branches we will be creating.
- This number will help us identify what issue we will be talking about.

