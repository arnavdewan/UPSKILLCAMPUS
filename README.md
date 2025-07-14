# 💉 Vaccination Portal – Full Stack Project (Teeka-Kendra)

**Teeka-Kendra** is a full-stack web application built to streamline the vaccination appointment process.  
It allows users to register, log in, manage child/adult vaccination appointments, and track vaccination status — all in one place with a clean and user-friendly interface.

---

## 🚀 Features

### 👤 User Authentication
- Signup and login using mobile number and password
- Backend-based session handling using Node.js and Express

### 📅 Appointment Management
- Register children and adults for vaccination
- Book, update, and cancel appointments
- View confirmation and track vaccination status

### 🌙 UI Enhancements
- Animated tagline on the homepage
- Real-time clock display
- Dark mode toggle

---

## 🧰 Tech Stack

| Layer      | Technology                        |
|------------|------------------------------------|
| Frontend   | HTML, CSS, JavaScript, React       |
| Backend    | Node.js, Express.js                |
| Database   | MongoDB (Atlas)                    |
| Versioning | Git & GitHub                       |

---

## 📁 Project Structure

vaccination-portal/
│
├── backend/ # Express.js server
│ ├── routes/ # API routes (auth, appointments)
│ ├── models/ # Mongoose schemas
│ ├── server.js # Entry point
│ └── .env # Environment variables
│
├── react/ # React-based frontend components
├── *.html, *.js, *.css # Static files (for simpler UI pages)
├── .gitignore
├── package.json
└── README.md



---

## 🛠️ Getting Started Locally

### 🔧 Backend Setup

1. **Clone the repository:**

```bash
git clone https://github.com/arnavdewan/vaccine2.git
cd vaccine2/backend
Install dependencies:

bash
Copy
Edit
npm install
Create a .env file in backend/ folder and add:

env
Copy
Edit
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/vaccinationDB?retryWrites=true&w=majority
PORT=5000
Start the server:

bash
Copy
Edit
npm run dev
💻 Frontend Setup
If using static HTML + JS:
Open login.html, signup.html, or dashboard.html in your browser directly.

If using React:
Navigate to the React folder:

bash
Copy
Edit
cd ../react
npm install
npm start
📬 Author
Arnav Dewan
🎓 Vellore Institute of Technology, Vellore
📧 arnavdewan05@gmail.com
🌐 @arnavdewan
