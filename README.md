# CRUD_Node_Excel

Title: CRUD Application with Node.js and Excel as Database

Description:
This repository contains a simple CRUD (Create, Read, Update, Delete) application built using Node.js, Express, and an Excel spreadsheet as the database. The backend of the application is designed to handle RESTful API endpoints for managing phone numbers. The data is stored and retrieved from an Excel file, acting as a lightweight database.

Features:

Create a new phone number: HTTP POST request to '/data' endpoint.
Update a phone number by ID: HTTP PUT request to '/update-phone/:id' endpoint.
Delete a phone number by ID: HTTP DELETE request to '/delete-phone/:id' endpoint.
Get all phone numbers: HTTP GET request to '/get-phones' endpoint.
How it works:

The application reads data from the 'data.xlsx' Excel file when necessary.
To create a new phone number, a POST request with the phone number data is made, and the data is appended to the Excel file.
To update a phone number, a PUT request with the phone number data and the ID is made, and the corresponding entry in the Excel file is updated.
To delete a phone number, a DELETE request with the ID is made, and the corresponding entry is removed from the Excel file.
To get all phone numbers, a GET request is made, and the application fetches the data from the Excel file and sends it as a JSON response.
Please feel free to explore the code and use it as a starting point for your own projects. If you encounter any issues or have suggestions for improvements, don't hesitate to open an issue or submit a pull request. Happy coding!

How to Use:

Clone the repository to your local machine.
Install Node.js and npm if you haven't already.
Install the required dependencies by running npm install.
Start the server with node app.js.
Access the CRUD application through http://localhost:3000.
Use a tool like Postman or cURL to test the API endpoints.

Note: This application is intended for demonstration and learning purposes. For production use, consider using a more robust database system.




