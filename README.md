#  Birthday Reminder RPA (UiPath)

## 📌 Overview
The **Birthday Reminder Bot** is an RPA solution built using UiPath that automates the process of sending birthday wishes via email.  
It reads persons data from an Excel file, checks for birthdays matching the current date, and sends personalized emails automatically.

---

## 🚀 Features
- 📊 Reads data from Excel (Name, Date of Birth, Email)
- 🔍 Identifies birthdays based on current date
- ✉️ Sends automated personalized birthday emails
- 🔁 Loop-based processing for multiple users
- ☁️ Integrated with Gmail using UiPath Integration Service
- ⚙️ Deployable via UiPath Orchestrator

---

## 🛠️ Technologies Used
- **UiPath Studio**
- **Excel Automation**
- **Gmail Integration (GSuite Activities)**
- **.NET (VB Expressions)**
- **UiPath Orchestrator**

---

## 📂 Project Structure
Birthday-Remainder/
│
├── Main.xaml # Main automation workflow
├── project.json # Project configuration & dependencies
├── Data/
│ └── Birthdays.xlsx # Input data file
└── README.md # Project documentation


---

## ⚙️ How It Works
1. The bot reads data from the Excel file.
2. Iterates through each row using a loop.
3. Extracts Date of Birth.
4. Compares day & month with current system date.
5. If matched:
   - Sends a personalized email via Gmail.

---

## 📸 Sample Workflow Logic
Read Excel → For Each Row → Check Birthday → Send Email


---

## 📧 Email Format
Subject: Happy Birthday 🎉

Dear [Name],

Wishing you a very Happy Birthday! 🎂🎉
Have a great day!

Best Regards


---

## ▶️ How to Run
1. Open the project in **UiPath Studio**
2. Ensure Excel file path is correct
3. Configure Gmail connection
4. Click **Run**

---

## ☁️ Orchestrator Deployment
- Publish project as `.nupkg`
- Upload to UiPath Orchestrator
- Create Process
- Trigger Job or Schedule

---

## ⚠️ Important Notes
- Gmail connection must be authorized
- Excel column names must match exactly:
  - Name
  - DateOfBirth
  - Email
- Date comparison uses **Day & Month only**

---

## 🔮 Future Enhancements
- 📅 Notify upcoming birthdays (next 3 days)
- 📩 Send bulk birthday greetings
- 📊 Add logging & reporting
- 📱 Integrate with WhatsApp/Teams notifications

---

## 👨‍💻 Author
**Adarsh K**

---

## ⭐ Acknowledgment
This project was developed as part of an RPA assignment using UiPath.

---
