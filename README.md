# [Board-Infintiy-Task](https://boardinfinityapi.herokuapp.com/)

Task Assigned By Board Infinity 
![](/projectSS.png)

You can Add task to database with Any Duration. After the Given Duartion task will automatically Gets deleted from the Database.
No need to Sign In / Sign Up in order to Add task. 

## USAGE

### How to Post Data

#### `POST` /add
This endpoint allows you to add Task to the DB.\
(Post data in JSON Fromat)
### 

#### i) User Can use Postman or any Other tool to Post Data.
#### ii) Use Form to Add Task 

### What are the Input Parameters for execute api call?

| Parameter  | Description                                                                                                                  |
|------------|------------------------------------------------------------------------------------------------------------------------------|
| "taskName"     | Should contain the Task Name (Required)                                                                        |
| "taskDescription" | Description about Task |
| "creater"    | Task Creater Name (Required)                             |
| "duration    | Duration (in Minutes) after which user want task to be deleted (Required) |

### How to See Tasks Present in DB

#### `GET` /list
This endpoint allows you to See Tasks that are Currently Present in DB.

#### OUTPUT
If the Output is like  [] (that means currently there is NO data present)

## Technology Used
This Project is Created using  ExpressjS, Node and MongoDb.

## Project Structure

#### `db` in db folder, there presnt a file conn.js which is used to connect to mongodb.<br />
There is Another folder in db i.e `models` in models schema is defined.

#### `routes` in this foler endpoints are defined

#### `views` in views View of Homepage is defined

### End Point of NO use :
There also present `/users` end Point Which is of No Use, that is Prefined When Express app is formed.

## Thank You
