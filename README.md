 # Livestock Management System

I built A comprehensive web-based application designed to manage various aspects of livestock on a farm, from basic animal records to health, breeding, feeding, vaccination, mortality, and movement data. This system demonstrates full-stack development capabilities using PHP and MySQL.
I still need to fix a table theres an sql issue with Vaccines
## Key Features

* **Full CRUD Operations:** Seamlessly Create, Read, Update, and Delete records for:
    * Farmers
    * Livestock
    * Health Records
    * Breeding Records
    * Feeding Records
    * Vaccination Records
    * Mortality Records
    * Movement & Sales Records
* **Relational Database Design:** Implements a multi-table MySQL database schema with appropriate relationships to ensure data integrity and organization.
* **Secure Data Handling:** Utilizes PHP Data Objects (PDO) with **prepared statements** to prevent SQL injection vulnerabilities.
* **Password Hashing:** Implements `password_hash()` for secure storage of user passwords.


## Technologies Used

* **Backend:** PHP 
* **Database:** MySQL
* **Frontend:** HTML, CSS, Vanilla JavaScript 
* **Server Environment:** WAMP

## How to Run

1.  **Clone the repository:** `git clone [YOUR_REPO_URL]`
2.  **Set up Database:**
    * Import the `livestock_management.sql` file into your MySQL database (e.g., via phpMyAdmin).
    Have WAMP server and mysql,

