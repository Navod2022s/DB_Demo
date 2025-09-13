# Java + MySQL Example

## Setup Instructions
1. Install MySQL Server (version 8.0 or later) and MySQL Workbench.
2. During installation, set a password for the `root` user.
   - Default user: `root`
   - Password: (whatever you choose during installation)
3. Create a database:
   ```sql
   CREATE DATABASE testdb;
   USE testdb;
   CREATE TABLE users (
       id INT AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(50),
       email VARCHAR(100)
   );
