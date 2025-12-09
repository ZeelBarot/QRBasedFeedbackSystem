# QR-Based Citizen Feedback System 🚀

A dynamic web application built using **HTML, CSS, JavaScript, PHP, and MySQL** to collect, store, and analyze citizen feedback through unique **QR codes**.  
Designed for digitizing feedback at public service centers, improving transparency, and simplifying administrative review.

---

## 📌 Features

- 📱 **QR Code–based feedback collection**  
- 📝 Simple & responsive feedback form UI  
- 🗂️ Stores submissions securely in MySQL database  
- 📊 Dashboard for viewing feedback (ratings, comments, service experience)  
- 🔐 Admin login panel for secure access  
- ⚡ Fast, lightweight, and mobile-friendly  

---

## 🛠️ Tech Stack

| Category      | Technologies |
|---------------|-------------|
| **Frontend**  | HTML5, CSS3, JavaScript |
| **Backend**   | PHP (Core PHP) |
| **Database**  | MySQL |
| **Tools**     | phpMyAdmin, XAMPP |
| **Other**     | QR Code Generator |

---

## 📂 Project Structure

```
QRBasedFeedbackSystem/
│
├── hackathon_22/                 <-- Main Project Directory/Branch 
│   │
│   ├── admin/                    <-- Admin Interface/Module 
│   │   ├── CSS/
│   │   ├── fonts/
│   │   ├── images/
│   │   ├── JS/
│   │   ├── pages/
│   │   ├── partials/
│   │   ├── SCSS/
│   │   ├── vendors/
│   │   │
│   │   ├── FIR_CHART.php 
│   │   ├── GP_logo.png 
│   │   ├── SELECT_DATA.PHP 
│   │   ├── TIME_TO_SOLVE_CHART.php 
│   │   ├── WAIT_TIME_CHART.php 
│   │   ├── admin.png 
│   │   ├── admindashbachup.php 
│   │   ├── admindashbackup.php 
│   │   ├── behaviour_chart.php 
│   │   ├── chart.php 
│   │   ├── dashboard.php 
│   │   ├── demo.php 
│   │   ├── dhello.php 
│   │   ├── feather.css 
│   │   ├── how_come_ps_chart.php 
│   │   ├── index.html 
│   │   ├── login.php 
│   │   ├── logo.png 
│   │   ├── police.jpg 
│   │   ├── ratingchart.php 
│   │   ├── style.css 
│   │   ├── table.php 
│   │   ├── temp.php 
│   │   ├── thello.html 
│   │   ├── thello.php 
│   │   ├── themify-icons.css 
│   │   └── vendor.bundle.base.css 
│   │
│   ├── officer/                  <-- Officer Interface/Module 
│   │   ├── CSS/
│   │   ├── fonts/
│   │   ├── images/
│   │   ├── js/
│   │   ├── pages/
│   │   ├── partials/
│   │   ├── SCSS/
│   │   ├── vendors/
│   │   │
│   │   ├── FIR_CHART.php 
│   │   ├── GP_logo.png 
│   │   ├── TIME_TO_SOLVE_CHART.php 
│   │   ├── WAIT_TIME_CHART.php 
│   │   ├── admin.png 
│   │   ├── bardoli.php 
│   │   ├── behaviour_chart.php 
│   │   ├── checking_credentials.php 
│   │   ├── dashboard.php 
│   │   ├── feather.css 
│   │   ├── how_come_ps_chart.php 
│   │   ├── index.html 
│   │   ├── logo.png 
│   │   ├── navsari.php 
│   │   ├── police.jpg 
│   │   ├── ratingchart.php 
│   │   ├── style.css 
│   │   ├── themify-icons.css 
│   │   └── vendor.bundle.base.css 
│   │
│   └── user/                     <-- User/Citizen Feedback Interface/Module ]
│       ├── PHPMailer/            <-- Library for email sending 
│       ├── CSS/
│       ├── fonts/
│       ├── images/
│       ├── js/
│       ├── pages/
│       ├── partials/
│       ├── SCSS/
│       ├── vendors/
│       │
│       ├── GP_logo.png 
│       ├── OTP.html 
│       ├── feather.css 
│       ├── form.html 
│       ├── form.php 
│       ├── form1.php 
│       ├── form2.php 
│       ├── index.html 
│       ├── insert_data.php 
│       ├── logo.png 
│       ├── mail.php 
│       ├── otp.php 
│       ├── remail.php 
│       ├── select2-bootstrap.min.css 
│       ├── select2.min.css 
│       ├── send.PHP 
│       ├── style.css 
│       ├── thankyou page.html 
│       ├── themify-icons.css 
│       ├── vendor.bundle.base.css 
│       └── Login_qr_code.png 
│
├── hackathon.csv 
├── README.md 
└── QR Code based citizen feedback system for Gujarat Police.pdf
```

## 🚀 Installation & Setup

### 1️⃣ Clone the repository
```
git clone https://github.com/yourusername/QRBasedFeedbackSystem.git
cd QRBasedFeedbackSystem/hackathon_22
```

### 2️⃣ Move project to your local server directory

- XAMPP: C:/xampp/htdocs/QRBasedFeedbackSystem

- WAMP: C:/wamp64/www/QRBasedFeedbackSystem

- LAMP: /var/www/html/QRBasedFeedbackSystem

### 3️⃣ Import the database

- Open phpMyAdmin

- Create a new database (e.g., feedbackdb)

- Import hackathon.csv or your .sql export

### 4️⃣ Configure database connection

Edit insert_data.php, checking_credentials.php, or config.php:

```
$connection = mysqli_connect("localhost", "root", "", "feedbackdb");
```

### 5️⃣ Run the system

Open:

```
http://localhost/QRBasedFeedbackSystem/hackathon_22/user/form.php
```

Or QR-scanned link.

## 🔍 How the System Works

1. QR code is generated for each police station / service point.
2. User scans the QR and is redirected to the feedback form.
3. User fills ratings, selects categories, and submits the form.
4. Data is stored securely in MySQL.
5. Admin & Officers log in to view:
   - Daily/weekly feedback
   - Rating charts (bar, line, pie)
   - FIR, wait time, behavior, and service charts
6. Export options allow admins to download reports for analysis.

## 📸 Screenshots

![User Feedback Form](screenshots/form.png)
![Admin Dashboard](screenshots/dashboard.png)
![Officer Panel](screenshots/officer.png)
![QR Code](screenshots/qrcode.png)

## 🔮 Future Enhancements

- Firebase / MERN version with real-time analytics  
- AI-powered sentiment analysis for comments  
- Role-based dashboards (Admin, Officer, Supervisor)  
- SMS / Email OTP verification  
- Cloud deployment (Render, Vercel, Firebase Hosting)  
- Automated reporting with PDF export  

## 🤝 Contributing

Contributions, issues, and feature requests are welcome.  
Feel free to open a Pull Request.

## 🧾 License

This project is licensed under the **MIT License**.

## 📬 Contact

**Zeel Barot**  
Email: zeelbarot945@gmail.com  
GitHub: https://github.com/ZeelBarot  
LinkedIn: https://linkedin.com/in/zeel-barot-94058b26b
