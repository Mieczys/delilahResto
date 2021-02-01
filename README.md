# Delilha Restó :zap:
https://github.com/Mieczys/delilahResto


Delilah Restó is a restaurant web application. This project contains the backend component of the system, which in general is an product catalog and order manager.

## Installation

### HTTP Server and Database

The Delilah Restó system runs with a MySQL database, so the MySQL Database engine must be installed.

1. Install XAMMP

2. Start both Apache and MySQL

3. Open the MySQL Admin

4. Create a new database

5. Name the new database as “delilah_resto” and click on create

6. Click on “import”

7. Click on select

8. Select the “delilah_resto.sql” file attached in the project folder

9. Go


### Express Server

1. Install NodeJS (https://nodejs.org/es/)
2. Open CMD Terminal in Visual Studio Code
3. Ensure the path in the command matched the absolute path of the routes folder in your pc.

```bash
\delilah_resto\
```

4. Run the following command “npm install”, and wait for it to finish

```bash
\delilah_resto\> npm install
```

5. Run the following command “CD routes”

```bash
\delilah_resto\> CD routes
```

6. Run the following command “node index.js”

```bash
\delilah_resto\routes> node index.js
```

## Usage

In order to know about the use of this API please refer to the .yaml file to see the swagger OpenAPI API file description.

## Testing

Use Postman to test all the endpoints available in the API. All requests have been tested previously so there is a request Postman collection available inside the project folder inside the “attachments” folder, “Delilah Restó.postman_collection.json”.
