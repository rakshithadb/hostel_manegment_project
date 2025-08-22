# hostel_manegment_project

This project is a GUI-based Hostel Management System developed using Python (Tkinter) and SQL. It simplifies hostel operations like room allocation, fee tracking, student and staff record management, and includes authentication for secure access.

Features

Student Management: Add, update, view, and delete student records.

Room Allocation: Track and assign rooms to students efficiently.

Fee Tracking: Maintain payment history and pending fees.

Staff Management: Store and manage staff details.

Authentication: Role-based login (admin, staff).

User-Friendly Interface: Built using Tkinter for ease of use.


Tech Stack

Frontend: Tkinter (Python GUI)

Backend: Python

Database: MySQL / SQLite

IDE/Tools: VS Code
How to Run

1. Clone the repository:

git clone https://github.com/<your-username>/hostel-management-system.git
cd hostel-management-system


2. Install dependencies:

pip install -r requirements.txt


3. Database setup:

Import the provided hostel.sql file or create tables manually.

Update database credentials in config.py (if applicable).



4. Run the application:

python main.py



Folder Structure (Example)

hostel-management-system/
│
├── main.py             # Entry point
├── config.py           # DB configuration
├── database/           # SQL scripts
├── modules/            # Student, Room, Staff modules
├── assets/             # Images/icons (if any)
└── README.md
