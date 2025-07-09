# Task Assignment & Reporting System

A web-based tool built with Python and Streamlit to streamline team task management, progress tracking, and daily reporting.

---

## 🔧 Tech Stack
- Python
- Streamlit
- Streamlit Authenticator
- Google Sheets API
- Excel (Pandas)
- SMTP (Email)

---

## 🚀 Key Features
- 🔐 **Secure Login System** – User authentication using hashed passwords  
- 📝 **Task Assignment Dashboard** – Assign, update, and view tasks team-wise  
- 📧 **Daily Email Alerts** – Task updates/notifications sent automatically via email  
- 📊 **Excel-based Reports** – Downloadable and filterable reports for team tasks  
- 🔄 **Google Forms Sync** – Automatically fetch task updates using Google Sheets API  
- 🌐 **Web Interface** – Simple and interactive UI using Streamlit

---

## 📁 Project Structure
task-system/
├── main.py
├── auth_config.yaml
├── tasks.csv
├── utils/
│ ├── email_sender.py
│ ├── google_sheets.py
├── requirements.txt

yaml
Copy
Edit

---

## 💡 How to Run
1. Clone this repo  
2. Install required packages:  
pip install -r requirements.txt

javascript
Copy
Edit
3. Set up `auth_config.yaml` with hashed passwords  
4. Set up access to Google Sheets API  
5. Run the app:  
streamlit run main.py
