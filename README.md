# SB Works – Freelancer Finder 💼

A full-stack MERN application that connects clients with freelancers for seamless project collaboration, bidding, and communication.

## 🚀 Live Demo
[🔗 Demo Link](https://drive.google.com/drive/folders/1qMc5a5ohuFAnlZhHpiQUpNvX5ICipNoj?usp=sharing)

## 🛠 Tech Stack
- **Frontend:** React.js, Bootstrap, Material UI, Axios  
- **Backend:** Node.js, Express.js, MongoDB, Mongoose  
- **Auth:** JWT, bcrypt  
- **Tools:** Postman, MongoDB Compass, VS Code  

## ⚙️ Features
- 📝 Project Posting & Bidding  
- 🔐 Secure Authentication (JWT)  
- 👤 Role-Based Dashboards (Client, Freelancer, Admin)  
- 📬 In-App Messaging (Basic)  
- 🛡️ Admin Moderation  

## 📦 Setup Instructions

### Prerequisites
- Node.js, MongoDB, Git

### Installation
```bash
git clone https://github.com/Harithasaibarma/freelancer_finder.git
cd freelancer-app-MERN

# Install frontend dependencies
cd client && npm install

# Install backend dependencies
cd ../server && npm install
Environment Setup
Create .env in /server:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
Run Locally

# Start backend
cd server && npm start

# Start frontend
cd ../client && npm start
Visit: http://localhost:3000

📌 API Routes
POST /api/auth/register – Register

POST /api/auth/login – Login

GET /api/projects – View all projects

POST /api/projects – Post a new project

POST /api/bids – Place a bid

GET /api/bids/:projectId – View bids

🧪 Testing Tools
Postman (API)

MongoDB Compass (DB)

Chrome DevTools (UI)

👨‍💻 Team
Bolleddula Vivek Rahul Rai – Backend, Architecture 

Battu Baby Sarojini – Frontend (UI)

Batraju Vamsikrishna – API Integration, Deployment

Barama Haritha Sai – Testing, Docs, Support
