# GreenSwap

GreenSwap is a **server-side PHP web application** developed as a **Level 6 (Year 2) college project**.  
The project demonstrates core web development concepts including dynamic pages, database integration, and CRUD workflows.

> Note: This repository is a **fork** of the original project repository.

---

## Tech Stack

- **PHP** (server-side logic)
- **MySQL / SQL** (database)
- **HTML / CSS** (UI)
- **JavaScript** (basic client-side functionality)

---

## Features

- Dynamic product and category listing pages  
- Database-backed content rendering (products/items)  
- CRUD workflows (e.g. create product/listing pages)  
- Basic input handling and validation  

---

## My Contributions (Highlights)

Some of the key areas I personally contributed to include:

- Developed and maintained the **navigation bar**, ensuring all navigation links correctly routed to their respective pages.  
- Built and updated a **dynamic, server-rendered product listing page** to display items retrieved from the database.  
- Improved database access by implementing **prepared statements (parameterised queries)** to enhance security and maintainability.  
- Enhanced the **Create Product** CRUD functionality by adding additional fields (e.g. product description) and improving form structure and consistency.

---

## Project Structure (High Level)

- `Website/` – main application source  
  - `public/` – public pages and CSS  
  - `private/` – functions, CRUD scripts, and database connection logic  

*(Exact structure may vary depending on environment setup.)*

---

## Running Locally

This is a PHP + SQL project, so a local environment usually includes:

- **XAMPP** (or PHP built-in server)
- A local **MySQL** database
- Imported SQL schema/data (if included)

### General Steps
1. Clone the repository  
2. Place the project inside your web server directory
3. Create the database and import the SQL file (if provided)  
4. Update `database_connection.php` with local database credentials  
5. Run the application via `localhost`  

---

## Credits / Academic Context

This project was completed as part of **second-year coursework** and reflects the skills developed at that stage of the degree.  
Some learning resources used included online documentation and tutorials (e.g. W3Schools).
