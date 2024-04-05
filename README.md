SunBase Backend Project
Assignment Project
This repository contains the codebase for a backend API that manages customer information. The assignment involves implementing various CRUD operations and later extending the functionality in the second phase to synchronize customer data from a remote API.

Assignment Completion
The following API endpoints have been implemented in the initial phase: In my case i use http://localhost:8080/home then api end point

Create a Customer

Path: /api/customers
Method: POST
Description: Create a new customer in the system.
Update a Customer

Path: /api/customers/{customerId}
Method: PUT
Description: Update an existing customer's information.
Get a List of Customers

Path: /api/customers
Method: GET
Description: Retrieve a paginated, sorted, and searchable list of customers.
Get a Single Customer Based on ID

Path: /api/customers/{customerId}
Method: GET
Description: Retrieve details of a specific customer based on their ID.
Delete a Customer

Path: /api/customers/{customerId}
Method: DELETE
Description: Delete a customer from the system.
Serach a Cutomer by Name, Email, State etc

Path: /api/customers/search
Method: GET
Description: Serach a Cutomer by Name, Email, State, City
Second Phase
In the second phase, additional functionality has been added:

Synchronize Customer List
Description: A button named "Sync" has been added on the customer list screen. Clicking this button triggers a call to a remote API to fetch the customer list. The retrieved customers are then saved in the local database. If a customer already exists in the database, their information is updated instead of inserting a new record. for this you need to download frontend repositor or use postman (for postman:http://localhost:8080/home/api/customers/search/sunbase)

Frontend Code Link

https://github.com/Aasif9/Customer-Management-Frontend

Setup and Usage
Clone the repository.
Set up the backend environment.
Run the backend server.
Clone the fronted code.
Run the frontend code.
