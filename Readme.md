liquibase commands

->mvn liquibase:update
->mvn liquibase:dropAll
->mvn liquibase:generateChangeLog (compare the existing changes from database with the current changes and then create a actual change log file)
->doesnot support for triggers, stored procedures and functions( those should be generated separately)
->mvn liquibase:updateSQL
    
    