# [NewsPortal ](https://github.com/pkminor/NewsPortal)

Author [Patrick Maina](https://github.com/pkminor)

## Brief description
NewsPortal is an Organisational news dissemination application. 
Users can post news to the general staff or to staff in a specific department.

## User Requirements   

The user would like to;
- Create departments
- Create news and categorize then as general or belonging to a specific department
- Add users to a department where one department has many users
- See individual users, their details like position,role and department.
- See department details like name, details and number of employees in the department
- See all users from a specific department and news relating to that department
- Post general news or news relating s a specific department.

## How it works

# Server Side

The application has four model classes;
- User
- News
- DepartmentNews
- Department

DepartmentNews inherits from News.
In the database, model User maps to table users, model Department maps to table departments while model
News and model DepartmentNews map to one table news through single table inheritance.

Three dao interfaces and their corresponding implementation classes;
- Interface UserDao implemented by class Sql2oUserDao, handles CRUD data operations related to model User.
- Interface NewsDao implemented by class Sql2oNewsDao, handles CRUD data operations related to model News and DepartmentNews.
- Interface DepartmentDao implemented by class Sql2oDepartmentDao, handles CRUD data operations related to model Department.

# Client Side

## Setup Instructions
Fork the project on github [NewsPortal ](https://github.com/pkminor/NewsPortal), then clone it to your local repo.

## Technology used
 - Java
 - SparkJava
 - Gradle
 - JUnit 4
 - Git VCS
 - IntelliJ IDEA Community Edition
 - Postgres
 - Sql2o
 - AngularJs
 
## Known Bugs
There are no known bugs. Please submit those you find for correction.

## Contributing
Pull requests are encouraged.

## License
This project is licensed under the MIT Open Source license.
