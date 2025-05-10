# Clinical Data Warehouse UI — Final Project (HI 741)

This project is a Python-based desktop application designed for hospitals to manage patient records and clinical notes securely and efficiently. The interface is built with **Tkinter** and offers **role-based access** for different user types (e.g., clinicians, nurses, admins, and management).

---

## 🚀 Features

- 🔐 **Login with Credential Validation**
- 📋 **Add / Remove / Retrieve Patient Records**
- 📝 **View Clinical Notes by Date**
- 📊 **Generate Key Statistics**
- 📆 **Count Visits by Date**
- 🧾 **Automatic Usage Logging**
- 🔒 **Role-Based Access Control**

---

## 🧑‍⚕️ User Roles & Access

| Role        | Permissions                                                    |
|-------------|----------------------------------------------------------------|
| `clinician` | Full access to all patient features and clinical notes         |
| `nurse`     | Same access as clinicians                                      |
| `admin`     | Can only count patient visits                                  |
| `management`| Can only generate key statistics (no patient data access)      |

---

## 🗂️ Project Structure

Anthony_Campbell_FinalProject/
├── main.py
├── ui_app.py
├── patient.py
├── user.py
├── utils.py
├── README.md
├── requirements.txt
├── UML_Diagram.png (optional)
├── data/
│ ├── credentials.csv
│ ├── patients.csv
│ └── notes.csv
└── output/
├── usage_log.csv
└── updated_patients.csv

yaml
Copy
Edit

---

## ⚙️ How to Run the App

### 1. Set up your Python environment
Install Python 3.x if you haven’t already:
- https://www.python.org/downloads/

### 2. Install required packages
```bash
pip install -r requirements.txt
3. Run the application
bash
Copy
Edit
python main.py
A login window will appear. Use credentials from credentials.csv to log in.

📦 Requirements
Python 3.x

pandas

matplotlib

tkinter (pre-installed with Python)

📝 Notes
Make sure the /data and /output folders are in the same directory as main.py.

Usage logs and updated patient files are saved automatically after each session.

📅 Author & Course Info
Name: Anthony Campbell
Course: HI 741 – Programming for Health Informatics
Instructor: Dr. Lu He
Semester: Spring 2025

