📘 College Management & Digital Infrastructure System
A Complete Institutional Automation Platform for Kash College
<p align="center"> <img src="https://img.shields.io/badge/Backend-Node.js-green?style=for-the-badge"> <img src="https://img.shields.io/badge/Database-MongoDB-brightgreen?style=for-the-badge"> <img src="https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20EJS-blue?style=for-the-badge"> <img src="https://img.shields.io/badge/Status-In%20Development-yellow?style=for-the-badge"> </p>
🚀 Project Overview

A full-stack institutional automation platform built for Kash College, aimed at digitalizing 95% of academic, administrative, residential, sports, library, and inventory workflows.

Designed with scalability, data security, and long-term automation in mind.

🛠 Tech Stack
Category	Technologies
Frontend	HTML, CSS, EJS Templates, Bootstrap/Tailwind
Backend	Node.js, Express.js
Database	MongoDB
Integrations	Excel/CSV Export, SMTP Email, Payment Gateways
Developer	Subhankar Pandit – Full Stack Developer, Backend Engineering
✅ Completed Features
🎓 Academic System

Curriculum structure (Unit → Chapter → Topic → Subtopic)

Staff & faculty module

IT & admin staff

Purchases & procurement

Department-wise inventory

Accounts (Purchase tracking)

Lab management (inventory, attendance, equipment)

Subjects & lab mapping

Test management for MAT / CAT / VST / PTS / Test Exam / Annual

Timetable system

Noticeboard + event scheduler

Lesson plan & progress tracking

Principal performance review

Monthly budgeting

Academic calendar

🏫 Residential System

Sick management

Medicine inventory

General hostel inventory

🏋️ Sports System

Sports equipment inventory

Purchase tracking

🍽 Kitchen System

Inventory management

Staff attendance

📚 Library System

Book inventory

Book registration

📦 Additional Inventories

Assets

Plumbing, Electrical, RO, DG

Garden & Misc items

Stationery & Cleaning items

Medicine Stock

📤 Exports

Export: Student list

Export: Staff list

Export: All inventories

❌ Pending Features (Not Done Yet)

These are the modules you specifically marked as NOT completed.

❗ Academic Pending

Admission (SAMS portal)

Fees

Scholarships

Class & lab attendance (final model)

Quiz bank

Teacher performance review

Notifications system

Extracurricular activity reporting

❗ Transport Pending

Transport schedule system

❗ Residential Pending

Separate boys/girls attendance

Hostel exit item return system

❗ Kitchen Pending

Mess menu & timings

❗ Library Pending

Issue & return system

❗ Inventory Downloads Pending

Staff / Student / Inventory export (final version)

Attendance export

Exam results export

Fee payment export

❗ Sponsorship & Donations Pending

Sponsorship module

Donation module

ICICI / Axis integration

Razorpay integration

❗ Alumni Pending

Auto move to alumni

Bulk email to alumni

❗ Dashboards Pending

Student dashboard

Parent dashboard

Staff dashboard

❗ Staff Pending

Joining tracker (1-year unlock logic)

❗ Student Pending

SAMS portal integration

❗ Women’s Cell Pending

Safety environment

Grievance redressal

Confidential complaint mechanism

Gender sensitivity programs

🧱 System Architecture
flowchart TD
    A[Frontend<br>HTML • CSS • EJS] --> B[Express.js Backend]
    B --> C[Academic Module]
    B --> D[Residential Module]
    B --> E[Kitchen Module]
    B --> F[Library Module]
    B --> G[Sports Module]
    B --> H[Inventory Module]
    B --> I[Sponsorship & Donations]
    B --> J[Alumni]
    B --> K[Payments]
    B --> L[Email/Notifications]
    B --> M[MongoDB Database]

⚙️ Installation & Setup
# Clone repository
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

# Install dependencies
npm install

# Setup .env file
PORT=
MONGO_URI=
EMAIL=
EMAIL_PASS=
RAZORPAY_KEYS=
ICICI_AXIS_KEYS=
JWT_SECRET=

# Start server
npm start

🗺️ Future Enhancements

Role-based dashboards with analytics

Final SAMS portal integration

AI-driven academic performance insights

Mobile app (React Native / Flutter)

Automated alumni workflow

Biometric attendance integration

👨‍💻 Developer

Subhankar Pandit
Full Stack Developer | Backend Engineer | AI/ML
🔗 GitHub: https://github.com/SubhankarA8415

🔗 LinkedIn: https://linkedin.com/in/subhankar-pandit

LinkedIn: https://linkedin.com/in/subhankar-pandit
