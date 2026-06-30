# phpMyAdmin-and-MongoDB-MySQL
Attached are sample screenshots from a MySQL database project I developed. The project involved building a fully‑structured banking database, including schema design, user permissions, and secure data handling.

The image below shows the initial creation of the MySQL banking database using MariaDB. I built a structured Banking_database containing tables for accounts, audits, bank staff, customers, transactions, and users, each with defined permissions and access controls.

<img width="975" height="297" alt="image" src="https://github.com/user-attachments/assets/dc22ca19-f35c-437e-beca-0741961c12d2" />
The image below of how all the tables connect within the MySQL banking database, along with their respective permissions. This structure is essential for designing user privileges and managing access controls across the system.
<img width="975" height="491" alt="image" src="https://github.com/user-attachments/assets/ebc989a7-77ef-4ac4-8280-962e0bb72ffd" />
Below is a sample SQL command used to test the database’s functionality. In this example, I executed a DROP TABLE statement to remove the Audit table—an action generally not recommended unless necessary, as it permanently deletes the table and its data which can lead to other isssues for other Tables.

<img width="975" height="818" alt="image" src="https://github.com/user-attachments/assets/fe7938fe-f838-4878-8235-b9a6d4779e3e" />

The screenshots below showcase the same banking_database structure recreated in MongoDB. Unlike MySQL/MariaDB, which uses tables, MongoDB stores data in collections within a cluster, offering a non‑relational, document‑based approach to organizing the database in other words NoSQL.
<img width="975" height="545" alt="image" src="https://github.com/user-attachments/assets/9e3d2342-fe54-4585-8186-f84007b3bc74" />

