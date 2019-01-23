Stack tech
-maven 
-docker (later we require)
-java 8+
-spring 4
-intellij eclipse
-docker-compose (will be installed in docker)


Employee REST server

All data should be persisted into either memory initially later we will use a 
docker container and connect to it (preferable nosql). We will use spring data
for see this tranparency in the persistence.

Please demonstrate use of lambda, streams

We will  wrap response in ResponseEntity and will use a http code.

Also implement correct handle of exception and implement a exception handler 
(preferable from spring).

Please create branch and add comments indicating a description.

Create a web application that exposes REST operations for employees. 
The API should be able to:

Get employees by an ID
Create new employees
Update existing employees
Delete employees
Get all employees
An employee is made up of the following data:

Employee spec (example suggested ) in order to have a better design use dto 
ID - Unique identifier for an employee could be UUID
FirstName - Employees first name
MiddleInitial - Employees middle initial
LastName - Employeed last name
DateOfBirth - Employee birthday and year
DateOfEmployment - Employee start date
Status - ACTIVE or INACTIVE