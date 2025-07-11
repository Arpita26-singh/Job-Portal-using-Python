# Job-Portal-using-Python
The Job Portal is a Python-based application that allows job seekers and recruiters to interact on a single platform. It enables users to create profiles, search and apply for jobs, and helps employers to post jobs and manage applications.
🛠️ Technologies Used
Frontend (optional GUI): Tkinter / HTML (for web version)

Backend: Python

Database: SQLite3 / MySQL

IDE: VS Code / PyCharm / Jupyter Notebook

💡 Features
🔍 For Job Seekers:
Register and login securely

Create and update profile

Search jobs by title, company, or location

Apply to jobs

View application history

🧑‍💼 For Employers:
Register and login

Post new job listings

View all applications

Accept or reject candidates

🧱 Project Structure
bash
Copy
Edit
job-portal/
│
├── main.py                # Main entry point
├── db.py                  # Database setup and queries
├── user.py                # User-related functions (register/login)
├── jobs.py                # Job-related functionalities
├── employer.py            # Employer operations
├── utils.py               # Utility/helper functions
├── README.md              # Project documentation
└── requirements.txt       # Python packages required
⚙️ How to Run the Project
Clone the repository or download the files:

bash
Copy
Edit
git clone https://github.com/your-username/job-portal.git
cd job-portal
Install dependencies (if any):

nginx
Copy
Edit
pip install -r requirements.txt
Run the project:

css
Copy
Edit
python main.py
🧪 Sample User Credentials
Job Seeker

Username: arpita

Password: 1234

Employer

Username: hr_admin

Password: admin123

📂 Database Schema
Users Table: id, username, password, role, email

Jobs Table: job_id, title, company, description, location, posted_by

Applications Table: app_id, job_id, user_id, status

📝 Future Enhancements
Add email notification on application

Resume upload feature

Filter jobs by category or experience

Web-based interface using Flask/Django

👩‍💻 Author
Arpita Singh
BCA 2nd Year, Arka Jain University
