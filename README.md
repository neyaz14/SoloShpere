SoloSphere
🚀 SoloSphere is an online marketplace where users can post jobs, bid on projects, and securely process payments. Inspired by platforms like Upwork, SoloSphere connects freelancers with clients efficiently.

🌐 Live Demo
🔗 SoloSphere Live

📂 Repository
🔗 GitHub Repository

📜 Table of Contents
Features
Tech Stack
Installation
Usage
API & Backend
Configuration
License
Contributors
✨ Features
✔️ User authentication with JWT for security
✔️ Job posting & bidding system for freelancers
✔️ Search functionality to find jobs easily
✔️ Pagination for a seamless browsing experience
✔️ Stripe integration for secure payments
✔️ Framer Motion animations for a better UI experience

🛠 Tech Stack
Frontend (Client Side)
React.js
React Router
Tailwind CSS
Stripe Payment Gateway
JWT Authentication
Framer Motion
Backend (Server Side)
Node.js
Express.js
MongoDB
JWT for authentication
🚀 Installation
Clone the Repository
sh
Copy
Edit
git clone https://github.com/neyaz14/SoloShpere.git
cd SoloShpere
Client Setup
sh
Copy
Edit
cd client
npm install
npm start
Server Setup
sh
Copy
Edit
cd server
npm install
npm start
📌 Usage
Sign up/Login using a secure authentication system (JWT).
Post a job as a client, specifying details and requirements.
Browse jobs and place bids as a freelancer.
Search & filter jobs using the search functionality.
Secure payments through Stripe.
🔌 API & Backend
SoloSphere uses a Node.js and Express.js backend with a MongoDB database. JWT authentication ensures security.

Method	Endpoint	Description
POST	/api/auth/signup	User registration
POST	/api/auth/login	User login & JWT token
GET	/api/jobs	Fetch all job listings
POST	/api/jobs	Create a new job post
POST	/api/bids	Place a bid on a job
⚙️ Configuration
Environment Variables
Create a .env file in the server directory and add the following:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
STRIPE_SECRET_KEY=your_stripe_key
📜 License
This project is open-source and available under the MIT License.

👨‍💻 Contributors
🚀 Developed by neyaz14

