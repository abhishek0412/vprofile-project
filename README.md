# Prerequisites
#
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later
- This is updated to verify if the cehckin wnet well.
- This is another change. I need to pull it.
- This is another commit to check the pull commands.Pill actually fetch the changes and push it to local branch.
- This time it is for the fetch commands. Fetch only fetches the changes from remote and doesnt change cnything in your local branch.
# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
# Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


