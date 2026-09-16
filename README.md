# Student Management System

A console-based student management and college portal application built using Python and MySQL.

**Created by Ayush Sengar**

## Features

- Student login and authentication
- Student details
- Subject-wise attendance
- Overall attendance calculation
- Results and grade information
- Fee management
- Optional services
  - Transport
  - Hostel
  - Mess
  - Canteen
- Timetable
- Notices module (planned)

## Tech Stack

- Python 3
- MySQL
- mysql-connector-python
- python-dotenv

## Project Structure

```text
student_management_system/
│
├── .env.example
├── .gitignore
├── requirements.txt
├── student_management_db.sql
├── README.md
│
├── main.py
├── database.py
├── student.py
├── attendance.py
├── results.py
├── fees.py
├── timetable.py
└── notices.py
```

`.env` is required for local database configuration but is intentionally excluded from the repository for security reasons. Use `.env.example` as a template.

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/<your-username>/student_management_system.git
   cd student_management_system
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set up the database**

   - Create a MySQL database and import the schema:

     ```bash
     mysql -u <username> -p < student_management_db.sql
     ```

4. **Configure environment variables**

   - Copy `.env.example` to `.env`:

     ```bash
     cp .env.example .env
     ```

   - Fill in your database credentials (host, user, password, database name) in `.env`.

## Usage

Run the application from the project root:

```bash
python main.py
```

Follow the on-screen console prompts to log in and access student details, attendance, results, fees, timetable, and optional services.

## License

This project is licensed under the MIT License.

## Contact

**Ayush Sengar**

- GitHub: [@ayush-sengar-dev](https://github.com/ayush-sengar-dev)
- LinkedIn: [Ayush Sengar](https://linkedin.com/in/ayush-sengar-93ab57288)
- Email: ayushsengar717@gmail.com
