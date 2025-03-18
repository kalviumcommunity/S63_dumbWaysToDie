# Dumb Ways to Die - The Ultimate List of Bizarre Fatalities

## 🚀 About the Project
**Dumb Ways to Die** is a hilariously tragic web app that allows users to log in and maintain a personalized list of the weirdest and most bizarre ways people have met their end. Whether it's getting stuck in a vending machine, challenging a goose to a fight, or mistaking a superglue bottle for eye drops—this app is here to document the most ridiculous send-offs in human history.

Every user gets a unique list based on their preferences, which they can edit, update, and share. The project is built using the MERN stack and demonstrates various backend and frontend concepts.

---

## 🛠️ Tech Stack
- **Frontend**: React (Vite)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose for schema management)
- **Authentication**: Session-based Auth (Optionally Firebase Auth)
- **Deployment**: Render/Heroku for backend, Vercel/Netlify for frontend
- **API Testing**: Bruno/Postman

---

## 🎯 Features
- 🔐 **User Authentication** – Users can sign up, log in, and maintain their own list.
- 📜 **Custom Lists** – Each user sees their own "Dumb Ways to Die" list.
- 📝 **CRUD Operations** – Users can add, edit, and remove deaths from their list.
- 🔍 **Search & Filters** – Find specific types of bizarre fatalities.
- 📊 **Leaderboard** – Shows the top 10 dumbest ways to die as upvoted by the community.
- 🌐 **API for External Use** – Open API to fetch the most popular deaths.
- 🎭 **Dark Mode** – Because some deaths are better viewed in the dark.

---

## 📌 Proof of Work for ASAP Concepts
| Concept | Proof of Work |
|---------|--------------|
| ✅ **Project Setup, GitHub, and Launch** | Created a GitHub repo, initialized the project, and pushed the first commit. |
| ✅ **Dev Environment Setup** | Installed Node.js, MongoDB, and dependencies using npm. |
| ✅ **First API & Page** | Created an Express server and a basic React frontend. |
| ✅ **API Deployment (Local & Prod)** | Deployed API locally using Nodemon and to production on Render. |
| ✅ **API Testing** | Used Bruno/Postman for API requests. |
| ✅ **Mongoose Schema** | Defined a schema for storing deaths per user. |
| ✅ **Database Connection** | Connected MongoDB with Express. |
| ✅ **Modify Data via API** | Implemented APIs to add, update, and delete records. |
| ✅ **React App with Vite** | Set up the frontend using Vite and React. |
| ✅ **Frontend Deployment** | Hosted the frontend on Vercel/Netlify. |
| ✅ **Components for Entities** | Created a component to display the list of deaths. |
| ✅ **View List in React App** | Rendered user-specific lists dynamically. |
| ✅ **Insert, Update, Delete Operations** | Added full CRUD functionality in React. |
| ✅ **User Management via Bruno** | Tested user authentication and validation. |
| ✅ **Password Security & Session Storage** | Implemented password hashing and session storage. |
| 🔥 **Optional Enhancements** | Firebase Auth, caching, SSR, background jobs (optional). |

---

## 🚀 How to Run Locally
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/dumbways-to-die.git
   ```
2. Install dependencies for backend and frontend:
   ```bash
   cd dumbways-to-die
   npm install
   cd client
   npm install
   ```
3. Set up environment variables in `.env`:
   ```env
   MONGO_URI=<your_mongodb_uri>
   JWT_SECRET=<your_jwt_secret>
   ```
4. Start the backend server:
   ```bash
   npm run dev
   ```
5. Start the frontend:
   ```bash
   cd client
   npm run dev
   ```
6. Open `http://localhost:5173` in your browser.

---

## 📢 Contributing
If you have any ideas for more dumb ways to die, feel free to contribute! Fork the repo, make your changes, and submit a pull request.

---

## 📜 License
This project is licensed under the MIT License.

---

## 💬 Contact
For any queries or suggestions, reach out at [your email] or open an issue in the repo.

---

🎵 **"Dumb ways to die, so many dumb ways to die..."** 🎵
render deployed link https://s63-dumbwaystodie.onrender.com