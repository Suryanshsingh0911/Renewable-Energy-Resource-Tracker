🌱 Renewable Energy Resource Tracker
A full-stack web application to track, manage, and analyze renewable energy resources** such as solar, wind, and hydro systems. The platform provides real-time insights, project management, and energy tracking with an interactive dashboard.


🚀 Overview

The Renewable Energy Resource Tracker is designed to solve the problem of fragmented and inefficient energy monitoring systems. It offers a centralized platform where users can:

 Manage renewable energy projects
 Track energy production
 Monitor performance metrics
 Handle transactions and payments
 Visualize insights through dashboards


✨ Features

 🔐 User Authentication (Login/Register)
 ⚡ Energy Production Tracking (Energy Logs)
 🌍 Project Management (Solar/Wind/Hydro)
 📍 Location-based tracking
 💳 Transaction & Payment Management
 📊 Interactive Dashboard with insights
 🔄 RESTful API architecture
 📱 Responsive frontend design


🧠 Tech Stack

💻 Frontend
 HTML5
 CSS3
 JavaScript

⚙️ Backend
  Node.js
  Express.js

🗄️ Database
   MongoDB
   Mongoose

🛠️ Tools
   Git & GitHub
   Postman (API Testing)
   VS Code


📁 Project Structure
Renewable-Energy-Resource-Tracker/
│── models/
│   ├── User.js              # User schema (auth system)
│   ├── Project.js           # Energy projects
│   ├── EnergyLog.js         # Energy production data
│   ├── Transaction.js       # Payments & transactions
│   └── Location.js          # Location details
│
│── routes/
│   ├── authRoutes.js        # Login & register APIs
│   ├── projectRoutes.js     # Project management APIs
│   └── transactionRoutes.js # Transaction APIs
│
│── public/
│   ├── index.html           # Landing page
│   ├── login.html           # Login page
│   ├── register.html        # Register page
│   ├── dashboard.html       # User dashboard
│   ├── payment.html         # Payment UI
│   └── js/
│       ├── app.js           # Frontend logic
│       └── speed-insights.js
│
│── server.js                # Main server file
│── seed.js                  # Sample data generator
│── check_db.js              # DB connection check
│── run_pup.js               # Automation/testing script
│── test_map.js              # Testing
│── test_render.js           # Testing
│── package.json             # Dependencies
│── README.md




⚙️ Installation & Setup

1️⃣ Clone the Repository
git clone https://github.com/Suryanshsingh0911/Renewable-Energy-Resource-Tracker.git
cd Renewable-Energy-Resource-Tracker


2️⃣ Install Dependencies
npm install

3️⃣ Setup Environment Variables
Create a .env file in root:

PORT=5000
MONGO_URI=your_mongodb_connection_string

4️⃣ Run the Server
npm start

Server will run at:
http://localhost:5000


🔌 API Endpoints

🔐 Authentication

  POST /api/auth/register → Register user
  POST /api/auth/login → Login user

🌍 Projects

   GET /api/projects → Get all projects
   POST /api/projects → Create project
   PUT /api/projects/:id → Update project
   DELETE /api/projects/:id → Delete project

 💳 Transactions
 
   GET /api/transactions → Get all transactions
   POST /api/transactions → Add transaction


📊 System Workflow

1. User registers/logs in
2. Creates renewable energy projects
3. Adds energy production logs
4. System stores data in MongoDB
5. Dashboard displays analytics & insights
6. Transactions are recorded and managed


📈 Future Enhancements

 🔗 IoT integration for real-time energy sensors
 🤖 AI-based energy prediction
 📱 Mobile application
 🔐 Advanced authentication (JWT/OAuth)
 📊 Advanced analytics & charts


🧪 Testing & Utilities
 seed.js → Populate database with sample data
 check_db.js → Verify DB connection
 test_map.js, test_render.js → Debug/testing scripts
 run_pup.js → Automation (Puppeteer-based)



🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit changes
4. Push to GitHub
5. Open a Pull Request


📄 License
  This project is licensed under the MIT License.


👨‍💻 Author
  Suryansh Singh
 🔗 https://github.com/Suryanshsingh0911



⭐ Support
If you found this project useful:

⭐ Star the repository
🍴 Fork it
📢 Share it


💡 Final Note
  This project demonstrates how modern full-stack development can be used to solve real-world problems in renewable energy monitoring and sustainability.

