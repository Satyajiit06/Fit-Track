# 🏋️‍♂️ FitTrack

FitTrack is a modern fitness tracking web application that helps users manage their daily workouts and track exercise routines. Built with the MERN stack (MongoDB, Express.js, React, Node.js), it offers user-friendly interfaces for creating, updating, and monitoring workout progress.

## 🚀 Features

- 🧑‍💻 **User Authentication**: Secure signup and login using JWT.
- 📅 **Exercise Scheduler**: Create and manage workout plans.
- 📊 **Progress Tracking**: Monitor past workouts and progress over time.
- ⚙️ **CRUD Operations**: Add, edit, and delete workouts seamlessly.
- 💡 **Responsive UI**: Built with React for a smooth and responsive experience.

## 🛠️ Tech Stack

- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Token)
- **Hosting**: *(Add hosting platforms if deployed — e.g., Vercel, Render)*

## 📂 Project Structure

\`\`\`
FitTrack/
├── client/ # React frontend
│ ├── src/
│ ├── public/
├── server/ # Node.js + Express backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── config/
├── .gitignore
├── README.md
└── package.json
\`\`\`

## ⚙️ Getting Started

### Prerequisites

- Node.js & npm
- MongoDB (local or MongoDB Atlas)

### Installation

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/Satyajiit06/Fit-Track.git
   cd FitTrack
   \`\`\`

2. Set up the backend:
   \`\`\`bash
   cd server
   npm install
   \`\`\`

3. Set up the frontend:
   \`\`\`bash
   cd ../client
   npm install
   \`\`\`

4. Add a \`.env\` file in the \`server\` folder with the following:
   \`\`\`env
   PORT=5000
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   \`\`\`

5. Run both frontend and backend:

   - Backend:
     \`\`\`bash
     cd server
     npm start
     \`\`\`

   - Frontend:
     \`\`\`bash
     cd client
     npm start
     \`\`\`

Visit \`http://localhost:3000\` in your browser.

## 🧠 Future Improvements

- 🏃‍♂️ Add timer for workouts
- 📅 Calendar view for schedules
- 📈 Graphs and analytics
- 🏆 Social leaderboard or sharing

## 🤝 Contributing

Contributions are welcome! Feel free to fork the project, make improvements, and create a pull request.

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
