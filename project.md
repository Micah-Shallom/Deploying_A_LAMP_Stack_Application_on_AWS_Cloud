## Deploying a LAMP Stack Web Application on AWS Cloud
***
A LAMP Stack is a solution stack that is being used in deploying web applications. It stands for Linux, Apache, MySql and php,perl or python. 

**Linux**: This is an operating system which serves as the backbone of the LAMP Stack, and it is actively used in deploying other components.

**Apache**: is a web server software which via HTTP requests processes requests and transmits information via the internet.

**MySQL**: use for creating and maintaining dynamic databases. It supports SQL and relational tables and provides a DBMS(Database Management System).

**PHP,PERL or PYTHON**: this represents programming languages which effectively combines all the elements of the LAMP stack and is used to make web applications execute.

First we log on to AWS Cloud Services and create an EC2 instance:

![EC2 Creation](./img/1.ec2_creation.png)


To deploying the web application, we need to install apache via ubuntu package manager `apt`:
```
#Updating Packages
sudo apt update

sudo apt install apache2
```

