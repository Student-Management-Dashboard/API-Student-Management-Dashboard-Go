# API-Student-Management-Dashboard-Go

![student_managment_dashboard_logo](https://user-images.githubusercontent.com/112921258/214308670-5b88bc63-03c1-4a80-8264-248238939957.jpg)

## What is Student Management Dashboard App?

Backend Service API for Student Management Dashbaord that provide teacher to manage student data and their progress from enrollment until graduate. Allow multiple teacher to give student feedback and track their performance.  Build using Golang with Echo Framework Based.

## Database Design

Database design using Entity Relationship Diagram.

![erd_student_management_dashboard](https://user-images.githubusercontent.com/112921258/214444833-5df9055d-8c7a-47b8-89fa-291071bebfb6.jpg)

## Open API Documentation

Explore our API at this [Documentation](https://app.swaggerhub.com/apis-docs/YUSNARSETIYADI150403/OPEN-API-DASHBOARD/1.0.0#/) powered by [Swagger.io](https://swagger.io/).

## Tech Stack

#### Code written based on

- Go Programming Language
- Echo Framework
- Gorm Package
- Mysql Database

#### Project Structure

Clean Architechture

#### Development

- Git Trunk Based Developepment
- Git Worklow CI/CD
- JWT Authentication
- Unit Testingn

#### Deployment

- Cloud Server Google Cloud Platform
- Docker Container
- File Repository Amazon S3 Service
- Cloudflre HTTPS/SSL

## Feature

- User can login and update data.
- Superadmin (Manager) can add other User (with various position such as Placement Team, People Skill team), update data and delete User.
- User can view all user list that registered
- User can create Class, Update, Delete and View Class List
- User can add Student Data, view Student list, update Student data, filter Student data by Class, Category (IT or Non IT) and Status (Interview, Join Class, Unit 1, Unit 2, Examp, Eleminated, Graduated)
- User can updat Student status
- User can add feedback for Student which other User can view the feedback.

## How to install and Run the Project

1.  Git clone this project
2.  Create mysql database
3.  Setup Environtment (check detail below)
4.  Open the main folder with your vs code
5.  Once it opened, open terminal in your vs code
6.  Run the program using "go run main.go"

## Environtment Setup

Create a file name ".env" and put at root folder of this project. Write this environtment detail below :

```
export DB_USERNAME=""
export DB_PASSWORD=""
export DB_HOST=""
export DB_PORT=""
export DB_NAME=""
export SERVER_PORT=""
export JWT_SECRET=""
export AWS_REGION=""
export AWS_BUCKET_NAME=""
export ACCESS_KEY_IAM=""
export SECRET_KEY_IAM=""
```

## Credits

Created by [M. Faishal](https://github.com/mfaishal882) and [Yusnar Setiadi](https://github.com/yusnarsetiyadi)
Thanks to our mentor [Fakhri](https://github.com/iffakhry)
