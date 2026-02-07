# gvp_AI_Hackathon_2026

# 📚 Smart Attendance & Performance Tracker
(Java Console-Based Application)

## 🔎 Introduction
Smart Attendance & Performance Tracker is a Java-based console application designed to manage student attendance and internal assessment records efficiently. It helps colleges avoid manual paperwork, reduce errors, and generate quick student performance insights.

---

## 🎯 Objectives
- Provide secure admin login
- Store student details
- Record attendance and marks
- Allow students to view reports
- Use JDBC for database connectivity

---

## 🛠 Technologies Used
- Java (Core Java)
- MySQL
- JDBC (Java Database Connectivity)
- VS Code / Eclipse

---

## 📐 System Architecture
User → Java Console App → JDBC → MySQL Database

---

## 👥 User Modules

### 1️⃣ Admin Module
- Login using username & password
- Add new students
- Enter attendance
- Enter marks

### 2️⃣ Student Module
- Enter roll number
- View attendance and marks report

---

## 🗄 Database Design

### Tables Used
1. **admin**
2. **students**
3. **attendance**
4. **marks**

### Table Structure

**students**
- roll_no (Primary Key)
- name
- course
- semester

**attendance**
- roll_no (Foreign Key)
- total_lectures
- attended_lectures

**marks**
- roll_no (Foreign Key)
- subject_marks

---

## 🔁 Application Workflow

1. Start Application
2. Display Main Menu
3. Admin Login / Student View
4. Database Interaction
5. Display Result
6. Exit

---

## 📊 Workflow Diagram (Text Representation)

Start → Main Menu → Decision  
→ Admin Login → Validate → Add Data → Save to DB → Back to Menu  
→ Student View → Enter Roll → Fetch Data → Show Report → Back to Menu  

---

## 🧪 Sample Output

SMART ATTENDANCE SYSTEM

Admin Login

Student View Report

Exit

Enter Choice: 1
Admin Username: admin
Password: admin123
Login Successful
Roll No: 1
Name: Snehal Kanpariya
Course: MCA
Semester: 2
Total Lectures: 20
Attended: 14
Marks: 72
Saved Successfully


---

## 🚀 How to Run the Project

1. Import database from `attendance_db.sql` into MySQL
2. Add MySQL Connector JAR to project
3. Compile:


---

## ⚠ Error Handling
- Invalid login message
- Duplicate roll number prevention
- Database connection validation

---

## 👍 Advantages
- Easy to use
- Secure admin access
- Reduces manual work
- Centralized data storage

---

## 👎 Limitations
- Console-based UI
- Single admin access
- No graphical interface

---

## 🚀 Future Enhancements
- Convert into Web Application
- Add GUI using JavaFX / Swing
- Role-based authentication
- Attendance percentage & AI remarks

---

## 🏁 Conclusion
Smart Attendance & Performance Tracker simplifies academic record management and improves efficiency. It is a strong foundation for future web-based systems.

---

## 👤 Author
Snehal
MCA – Semester 2  
