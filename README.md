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

The remaining screenshots display the SQL commands used to define the required data fields for each MongoDB collection within the cluster.

Account Information: 
<img width="975" height="587" alt="image" src="https://github.com/user-attachments/assets/c96f7be0-ebbb-4056-9a10-f2c1ec7e5c51" />

Audit information:
<img width="975" height="632" alt="image" src="https://github.com/user-attachments/assets/37f6cb0d-451d-4b32-8958-7ba1f8f6ada8" />

Bank Staff information:
<img width="883" height="687" alt="image" src="https://github.com/user-attachments/assets/353ef8db-7f5d-4057-b062-60e692d8e4c1" />

Customer Information:
<img width="975" height="907" alt="image" src="https://github.com/user-attachments/assets/6e15a1f3-c25a-48d1-8f85-ac5d961c5016" />

Transaction Information:
<img width="975" height="689" alt="image" src="https://github.com/user-attachments/assets/2473950b-7349-435f-af88-ba532765d190" />

User Information:
<img width="975" height="753" alt="image" src="https://github.com/user-attachments/assets/b3ba1119-9302-4af7-9d5b-e48bf60d30f2" />

Below are SQL queries demonstrating how user privileges and password requirements were configured within the database.

<img width="975" height="628" alt="image" src="https://github.com/user-attachments/assets/4b4a3101-9328-4a58-8268-3d62c7ab0911" />






