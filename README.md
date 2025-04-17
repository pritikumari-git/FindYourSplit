🧾 EasySplit
EasySplit is a full-stack MERN application designed to help users manage shared expenses efficiently. Whether it's splitting bills with roommates, friends, or travel buddies, EasySplit provides a simple and intuitive way to keep track of who owes what.


🚀 Features
🔐 Authentication

Register a new account

![Home](./assets/Home.png)

Login/logout functionality

Secure access to personal and group data

👥 Group Management

Create and join groups

Add members to a group

Set custom group cover images and names

💸 Expense Tracking

Add shared expenses in a group

Automatic split calculation

View total balance, amount owed, and amount to receive

✅ Settle Up

Settle all or individual dues

Reflects changes across all members in real-time

🧾 Expense List

See all past transactions for transparency

🛠️ Tech Stack
Frontend: React.js, Tailwind CSS (or Bootstrap/Material UI if applicable)

Backend: Node.js, Express.js

Database: MongoDB (with Mongoose)

Authentication: JWT (JSON Web Tokens)

State Management: React Context API or Redux

Routing: React Router, Express Router

📦 Installation
bash
Copy
Edit
# Clone the repository
git clone https://github.com/your-username/easysplit.git
cd easysplit

# Install backend dependencies
cd backend
npm install

# Start backend server
npm start

# Install frontend dependencies
cd ../frontend
npm install

# Start frontend server
npm run dev
Make sure MongoDB is running locally or provide a MongoDB Atlas connection string in your .env.

🌐 Environment Variables
In /backend/.env:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
📸 UI Preview
Group Dashboard

Expense Summary

Add Expenses

Member List with Roles

Settle Expenses Button

Responsive Design

🧠 Future Improvements
Email notifications for dues

Payment gateway integration

Group chat or comments under expenses

Dark mode support

🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.

