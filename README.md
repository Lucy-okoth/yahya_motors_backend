# YAHYA-MOTORS BACKEND

## INTRODUCTION
- This is a backend to <a href= https://github.com/Lucy-okoth/yahya_motors>yahya_motors </a> frontend

## AUTHORS
This project was contributed by : 
1. <a href=https://github.com/nicco99> Nicholas Njeru </a>
2. <a href=https://github.com/Lucy-okoth>Lucy Okoth</a>
3. <a href=https://github.com/esipil> Timothy Lenku/a>
4. <a href=https://github.com/Jidraf>Jidraph Ng'ang'a</a>
5. <a href=https://github.com/muthwi1234>Peter Kilungya</a>

## DESCRIPTION
This is a ruby, sinatra backend wich uses active record to interact with a database. 
The database used is the SQLite because it was the only known database by contibutors  at the time of this reading. The database will be switched to a postgress with time. 
Active record was used to create migrations between modules, use to create the migrations tables, migrated the data and also seeded the data to the database. 
Sinatra was used in running the server and creating the api endpoints.  


## Project Set Up
Fork and clone this repository to you local environment
cd to the cloned repo and open the repository with a code editor . 
In the terminal run the following command to install some packages. 
```console
$ bundle install
```
After installing, run the following code to migrate the table migration
```console
$ bundle exec rake db:migrate
```
You can the seed the database 
```console
$ bundle exec rake db:seed 
```
The database is set up, now you can run the server 
```console
$ bundle exec rake run server
```
This will run your server on port
[http://localhost:9292](http://localhost:9292).
