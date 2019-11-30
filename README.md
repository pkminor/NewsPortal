# [NewsPortal ](https://github.com/pkminor/NewsPortal)

Author [Patrick Maina](https://github.com/pkminor)

## Brief description
NewsPortal is an Organisational news dissemination application. 
Users can post news to the general staff or to staff in a specific department.

## User Requirements    

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

Three dao interfaces and their corresponding implementation class;
- Interface UserDao implemented by class Sql2oUserDao
- Interface NewsDao implemented by class Sql2oNewsDao
- Interface DepartmentDao implemented by class Sql2oDepartmentDao

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
