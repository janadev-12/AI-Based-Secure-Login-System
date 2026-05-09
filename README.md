AI Secure Login System

An advanced AI-powered secure authentication system built using **React, Node.js, Express, and MongoDB** with integrated cybersecurity and AI-based threat analysis features.

---

Features

Authentication

* User Registration
* User Login
* Protected Dashboard
* Session Management
* Logout System

---

Security Features

* bcrypt Password Hashing
* Session Protection
* CSRF Protection
* Rate Limiting
* Input Validation
* Error Handling Middleware
* Secure Environment Variables

---

AI Security Modules

Anomaly Detection :

Detects suspicious login activity and unusual behavior patterns.

Risk Scoring :

Calculates AI-based login risk levels.

Bot Detection :

Detects automated login attempts and brute-force attacks.

Password AI Analysis :

Checks password strength and security level.

Behavior Analysis :

Analyzes typing speed, mouse movement, and login patterns.

---

Frontend Features

* Modern Cybersecurity UI
* Glassmorphism Design
* Neon Glow Effects
* Animated Dashboard
* AI Security Analytics
* Responsive Layout
* Dynamic Risk Visualization

---

Dashboard Features

* Real-time AI Risk Score
* Login Activity Monitoring
* Bot Detection Status
* Security Analytics Cards
* Risk Analysis Charts
* User Activity Table

---

AI Dashboard Workflow

User Input → AI Analysis → Risk Calculation → Dashboard Visualization

---

Tech Stack

Frontend

* React.js
* React Router DOM
* Vite
* CSS3

Backend

* Node.js
* Express.js

Database

* MongoDB

Security

* bcrypt
* express-session
* express-rate-limit
* helmet

---

Project Structure

```bash
secure-login-system/

├── client/
│
├── server/
│   ├── ai/
│   │   ├── anomalyDetection.js
│   │   ├── behaviorAnalysis.js
│   │   ├── botDetection.js
│   │   ├── passwordAI.js
│   │   └── riskScoring.js
│   │
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── security/
│   ├── utils/
│   └── logs/
```

---

Installation

Clone Project

```bash
git clone <repository-url>
```

---

Install Backend

```bash
cd server
npm install
```

---

Install Frontend

```bash
cd client
npm install
```

---

Start MongoDB

```bash
mongod
```

---

Run Backend

```bash
cd server
npm run dev
```

---

Run Frontend

```bash
cd client
npm run dev
```

---

Open Application

```txt
http://localhost:5173
```

---

Environment Variables

Create `.env` inside `server/`

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/secure-login-system
SESSION_SECRET=mySuperSecretKey123
NODE_ENV=development
```

---

Test Flow

Register

Create a secure user account.

Login

Authenticate using email and password.

AI Analysis

System analyzes:

* bot behavior
* anomaly risk
* typing pattern
* password strength

Dashboard

View AI-generated security analytics.

---

Screens Included

* Home Page
* Login Page
* Register Page
* AI Dashboard

---

Future Improvements

* JWT Authentication
* Email OTP Verification
* Google Authentication
* Admin Panel
* Device Tracking
* Real Machine Learning Models
* Redis Session Storage
* Docker Deployment

---

Project Type

AI + Cybersecurity + Full Stack Authentication System

---

Developed By

JANAVANTH R

---

Final Status

✅ Fully Working
✅ AI Integrated
✅ Cybersecurity Focused
✅ Portfolio Ready
✅ Full Stack Project
