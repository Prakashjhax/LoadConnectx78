# LoadConnect 🚚📦

**Smart Logistics Platform for Efficient Load Booking & Transport**

LoadConnect is a web-based logistics platform designed to streamline rural-urban goods transport by minimizing empty return trips for commercial vehicles. It connects rural producers, urban buyers, and vehicle owners through a unified digital interface.

🌐 [Live Demo](https://loadconnectx78.netlify.app/)  
📂 [Project Repository](https://github.com/Prakashjhax/LoadConnectx78)

---

## 🌟 Features

- 📍 **Real-Time Location Integration** (Google Maps, Leaflet.js + OpenStreetMap)
- 🔒 **Secure Authentication** (JWT, bcrypt, OTP via Twilio)
- 📝 **Load & Vehicle Posting Modules**
- 📊 **Distance Calculator with Route Visualization**
- 🔄 **Booking and Quotation System**
- 📱 **Mobile-Responsive UI**
- 📥 **Document Uploads with Multer**

---

## 🎯 Objective

To eliminate empty return trips in logistics by enabling real-time load matching, vehicle tracking, and intelligent routing. This helps reduce fuel waste, boost transporter income, and support greener transportation solutions.

---

## 🛠️ Tech Stack

### Frontend
- HTML, CSS, JavaScript
- Google Maps API
- Leaflet.js + OSRM for distance calculation

### Backend
- Node.js, Express.js
- JWT, bcrypt.js, Twilio (OTP)
- Multer (file uploads)
- PostgreSQL (via `pg` module) hosted on Neon.tech

### Tools
- Postman (API Testing)
- Git & GitHub (Version Control)
- Visual Studio Code
- .env for environment configuration

---

## 📦 Folder Structure

LoadConnect/
│
├── client/ # Frontend code
│ ├── index.html
│ ├── style.css
│ └── script.js
│
├── server/ # Backend API
│ ├── routes/
│ ├── controllers/
│ ├── middlewares/
│ └── index.js
│
├── database/ # SQL schema and config
├── .env
├── package.json
└── README.md

yaml
Copy
Edit

---

## 👥 Team Members

| Name                     | Role          | Contributions                                    |
|--------------------------|---------------|--------------------------------------------------|
| Prakash Kumar Jha        | Frontend Lead | UI/UX, JS Logic, Map Integration, Docs           |
| Asit Kumar Jena          | Backend Lead  | APIs, Auth, Twilio, File Uploads                 |
| Akashy Kumar Kushwaha    | DB Engineer   | Schema Design, SQL, PostgreSQL Integration       |
| Nikhil Kumar Keshri      | Contributor   | N/A                                              |
| Chandrashekhar Kumar Jha | Contributor   | N/A                                              |

---

## 🚀 How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Prakashjhax/LoadConnect.git
   cd LoadConnect
Setup Backend

bash
Copy
Edit
cd server
npm install
npm run dev
Open Frontend
Open client/index.html in your browser.

Configure .env
Set up environment variables for:

PostgreSQL DB

JWT Secret

Twilio credentials

🧠 What We Learned
Building from scratch without frameworks improves core understanding.

Responsive UI challenges taught us advanced CSS and media queries.

Fullstack development taught integration between database, server, and UI.

Real-world problem-solving using technology and teamwork.

🧭 Future Enhancements
📡 Live vehicle tracking

📱 Android/iOS mobile app

🔔 Smart push notifications

🤖 AI-based load matching

💳 Digital payments (UPI, QR)

📈 Admin dashboard for insights

💬 Chatbot assistance

📚 References
W3Schools

MDN Web Docs

CodeWithHarry YouTube

ChatGPT

🔗 Useful Links
🌐 Website: loadconnectx78.netlify.app

📂 GitHub Repo: https://github.com/Prakashjhax/LoadConnectx78

🙏 Acknowledgements
Thanks to all teammates and online resources that helped us bring this idea to life. Special appreciation for ChatGPT’s guidance during debugging and development!

“Connecting rural roots to urban roads.”
