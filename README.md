# Blogging-Website
Building a blogging application with login/register using Flask WebApp performing CRUD operations. 

<hr>

![animation](Animation.gif)

<hr>

# Running 
Create database
```
mysql> CREATE DATABASE blog_db;
mysql> USE blog_db;
mysql> CREATE TABLE user(user_id int auto_increment,first_name varchar(20),last_name varchar(20),username varchar(20) unique,email varchar(30) unique,password varchar(100),primary key(user_id));
mysql> CREATE TABLE blog(blog_id int auto_increment,title varchar(100),author varchar(40),body varchar(1000),primary key(blog_id));
```
Insert MySQL password and database name (blog_db) in _db.yaml_ file

Install necessary python libraries as per _requirements.txt_ file
```
python app.py
```
