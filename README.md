# class_notes_dmdd

## DMDD NOTES from October 5 2022 by Professor Nik Brown
## Anshul Sharma - 002789548

### Table in database: 
Table in a database is a collection of data that is organized into rows and columns. Tables are used to store data in an organized manner and make it easier to find and retrieve specific data. Each table can have multiple columns and rows which can hold various types of data.

### ALTER TABLE:
ALTER TABLE is a SQL statement used to modify the structure of an existing table in a database. It is used to add, modify, or drop/delete columns in a table, or to add/drop/change indexes, rename the table, or change table options. ALTER TABLE is also used to add and drop various constraints on an existing table.

#### Example: ALTER TABLE Orders ADD OrderStatus INT;

### INSERT query:
Example: INSERT INTO customers (customer_id, first_name, last_name) VALUES (1234, 'John', 'Doe'); 
This query will add a new row to the customers table, with the customer_id being 1234, first_name being John, and last_name being Doe. 

### UPDATE query: 
#### Example: UPDATE customers SET first_name='John', last_name='Smith' WHERE customer_id=1234; 
This query will update the existing customer in the customers table with the customer_id being 1234, changing the first_name to John and the last_name to Smith. 

### CREATE query:
#### Example: CREATE TABLE customers (customer_id INT PRIMARY KEY, first_name VARCHAR(50), last_name VARCHAR(50)); 
This query will create a new table called customers, with the customer_id being an integer and the primary key, first_name being a varchar of length 50 characters, and last_name being a varchar of length 50 characters. 

### Localhost:
The localhost is the default name describing the local computer address also known as the loopback address. For example, typing: ping localhost would ping the local IP address of 127.0.0.1 (the loopback address). When setting up a web server or software on a web server, 127.0.0.1 is used to point the software to the local machine.

### URLstatus codes:
URL status codes are the numerical codes that indicate the status of a request made to a URL. They can indicate whether the request was successful (200), unsuccessful (404), or if the page is temporarily unavailable (503). These codes provide information about the status of a website and can help diagnose any problems that might arise when accessing the page.

### URL Body:
URL body is the part of a URL that is sent as part of an HTTP request. It includes the parameters and values that are sent to the server. This can include query strings, form data, and other data that is used to request a specific page or service from the server. The URL body is sent as part of the request header, and it is the part of the URL that can be seen in the browser address bar.

### SEO keywords:
SEO keywords are words and phrases that are used in web content to help search engines understand the context of a particular web page, so that they can deliver it as a relevant search result for someone looking for information. SEO keywords are also used by marketers to determine the effectiveness of their SEO campaigns by measuring the number of visitors who click through to the website from search engine results.

## Reference video shared by Professor:

SQL Basics for Beginners | Learn SQL | SQL Tutorial for Beginners | Edureka
https://www.youtube.com/watch?v=BPHAr4QGGVE
