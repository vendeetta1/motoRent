Moto rent project
=================

Application with functionality of rent motorcycle.

Used stack: Java, Spring Boot, Liquibase, Lambok, REST, PostgreSQL, Swagger.

The main functionality and implemented roles of the application:
Guest:
-	View the availability of motorcycle.
-	Arrange the rental of motorcycle.

Client:
-	Register
-	Arrange the rental of motorcycle.
-	Edit/view profile data.
-	Delete account.

Manager:
-	Change the rental data (cancel the order, postponement of the date, change of duration, etc.).
-	Invoicing for payment.
-	Changing/viewing customer data (passport, etc.).
-	Create a lease agreement (excel).
-	Change information about motorcycle. (availability, condition, etc.)

Administrator:
-	Create a new motorcycles.
-	Make changes to these motorcycles.
-	Delete/block equipment.
-	Edit/view/delete user profile.

Additional functionality:
-	Notification of the end of the CTP/Technical inspection.
-	Notification of fines GIBDD API (Client/Manager).