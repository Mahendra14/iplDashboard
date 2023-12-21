# iplDashboard
Implementing IPL Dashboard using React and Springboot, dataset from kaggle.


We start out with user experience, and then we go with system design and then implementation of the application.

I am using SpringBoot, and ReactJS for frontend, but because it is a view only application, hence there is no need of any external DB, using an in memory database and then populating it from an csv file in resources folder on startup (HSQLDB).

SpringBoot dependencies used are as follows:
 -  spring boot dev tools
 - spring web
 - hsql database
 - spring batch - to load up the csv file
 - JPA

I have taken reference from JavaBrains to build this application.