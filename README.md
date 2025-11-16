# satyamsql
Here is the updated **README.md** with an **Author** section added:
---
# SAITM Users Database

This project contains a MySQL dump file (`saitm_users.sql`) for the **SAITM users database**. It includes the table structure and sample data for a `users` table.

---
#### ✍️ Author

**Satyam Mishra**
Developer & Database Designer

---
## 📁 File Included

* **saitm_users.sql** – MySQL dump containing:

  * Table creation for `users`
  * Inserted sample data
---
## 🗂️ Table: `users`

The table contains the following fields:

* **name** – `VARCHAR(100)`
* **roll_no** – `INT`
* **grade** – `VARCHAR(10)`
* **marks** – `INT`

## 📥 How to Import the SQL File

1. Open **phpMyAdmin**, MySQL Workbench, or CLI.
2. Create a database (if not already):

   ```sql
   CREATE DATABASE saitm;
   ```
3. Import the file:

   * Using CLI:

     ```bash
     mysql -u your_username -p saitm < saitm_users.sql
     ```
   * Using phpMyAdmin:

     * Go to **Import** tab
     * Upload `saitm_users.sql`
     * Click **Go**

## 🧪 Sample Data Included

The SQL file contains sample entries for multiple users with names, roll numbers, grades, and marks.

---

## 📜 License

This project is free
