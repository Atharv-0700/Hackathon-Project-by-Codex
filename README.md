🎓 Smart Attendance Web App

Hackathon Project by Codex

A modern Smart Attendance Management System built as a web application to prevent proxy attendance and simplify classroom attendance using secure, real-time technologies.

🚀 Problem Statement

Traditional attendance systems face major issues:

❌ Proxy attendance by friends

❌ Manual errors & time consumption

❌ No real-time monitoring

❌ Poor scalability

💡 Our Solution

Smart Attendance Web App ensures:

✅ Secure student login

✅ Device binding (one device per student)

✅ QR-based attendance

✅ Teacher-controlled attendance sessions

✅ Real-time Firebase backend

✅ Clean & responsive UI

✨ Key Features
👩‍🏫 Teacher Features

Start / stop attendance sessions

Generate secure QR codes

View attendance history

Device management & monitoring

Reports & analytics dashboard

🎓 Student Features

Secure authentication

QR scan to mark attendance

Device fingerprint protection

Attendance history view

🔐 Security Features

Device fingerprint binding

Firebase Authentication

Real-time database rules

Proxy attendance prevention

🛠️ Tech Stack
Category	Technology
Frontend	React + TypeScript
Styling	Tailwind CSS
Build Tool	Vite
Backend	Firebase
Auth	Firebase Authentication
Database	Firebase Realtime Database
Deployment	Ready for Vercel / Netlify
📁 Project Structure
Smart Attendance Web App/
├── src/
│   ├── app/
│   │   ├── components/
│   │   ├── ui/
│   │   └── App.tsx
│   ├── config/
│   │   └── firebase.ts
│   ├── utils/
│   └── styles/
├── public/
├── index.html
├── package.json
├── vite.config.ts
└── guidelines/

⚙️ Setup & Installation
1️⃣ Clone Repository
git clone https://github.com/Atharv-0700/Hackathon-Project-by-Codex.git
cd Hackathon-Project-by-Codex

2️⃣ Install Dependencies
npm install

3️⃣ Firebase Setup

Create a Firebase project

Enable Authentication

Enable Realtime Database

Update credentials in:

src/config/firebase.ts

4️⃣ Run Locally
npm run dev


App will run on:

http://localhost:5173

🧪 Use Case Flow

Teacher logs in

Starts attendance session

QR code is generated

Students scan QR from registered device

Attendance is recorded instantly

Teacher views reports

🏆 Hackathon Value

✔ Solves a real-world education problem

✔ Scalable for colleges & universities

✔ Secure & modern architecture

✔ Clean UI/UX

✔ Production-ready structure

🔮 Future Enhancements

Face recognition verification

Location-based attendance (geo-fencing)

Excel / PDF export

Admin dashboard

Mobile app (Android)

👨‍💻 Team Codex

Built with ❤️ for hackathon innovation.
Focused on security, usability, and scalability.

📜 License

This project is for educational & hackathon purposes.
