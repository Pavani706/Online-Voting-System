
🗳️ Online Voting System — Web-Based Application

 📌 Introduction

The **Web-Based Online Voting System** is a digital platform designed to streamline and secure the voting process via the internet. This system eliminates the need for traditional paper-based voting, making elections more accessible, efficient, and convenient, especially for organizational or college-level elections.

📋 Project Overview

* Developed a secure, user-friendly online voting application.
* Built using **HTML, CSS, JavaScript**, and **Node.js** for backend functionality.
* Utilizes **MongoDB** as the database for storing user and voting data.
* Implements user registration, authentication, and real-time result updates.
* Designed specifically for **college elections** or small-scale organizations.

✨ Features

* 🔐 **Admin Panel**
  Manage candidates, view voter data, and oversee the voting process.

* 👤 **Voter Registration**
  New users can register before voting begins.

* 🗳️ **Voting Process**
  Secure and intuitive interface for casting votes for one of the predefined candidates.

* 📊 **Real-Time Results**
  Live tally and display of votes after successful voting.

 🛠️ Technologies Used

| Component   | Technology                                 |
| ----------- | ------------------------------------------ |
| Frontend    | HTML, CSS, JavaScript                      |
| Backend     | Node.js, Express.js                        |
| Database    | MongoDB                                    |
| Server Tool | Node.js (run locally or on cloud)          |
| Optional    | MongoDB Atlas (cloud DB)                   |
| Security    | (Optional) Mobile OTP verification via API |

 ✅ Requirements

* **Node.js** installed on your system.
* **MongoDB** installed locally, or use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for cloud DB.
* A modern browser (Chrome, Firefox, etc.).

 ⚙️ Installation Steps

#### 📥 STEP 1: Download the Zip File

* Download the project `.zip` file from the repository or link provided.

#### 📂 STEP 2: Unpack the Project

* Extract the `.zip` file to your preferred location.

#### 💻 STEP 3: Install Dependencies

* Open a terminal in the `backend/` folder:

  ```bash
  npm install
  ```

#### 🖥️ STEP 4: Start Backend Server

* Inside the same terminal:

  ```bash
  node server.js
  ```
* You should see: `Server running on http://localhost:5000`

#### 🌐 STEP 5: Open Frontend

* Navigate to the `frontend/` folder.
* Open `index.html` in your browser (double click or use Live Server in VS Code).

---

### 👥 Usage

#### 🔑 Admin Login

* **Username:** `rvrjcce`
* **Password:** `1290`

Once logged in:

* View and manage registered voters.
* Monitor vote counts.

#### 👤 Voter Flow

1. Enter your name in the registration form.
2. Once registered, proceed to vote.
3. Choose a candidate: **Pavani**, **Reehana**, or **Christy**.
4. Submit your vote.
5. View real-time results.

📎 Notes

* Make sure MongoDB is running before starting the server.
* If you're using **MongoDB Atlas**, update the `server.js` Mongo URI.
* You can replace the college logo in `index.html` with your own:

  ```html
  <img src="logo.png" alt="RVR and JC College Logo">
  ```

 ⭐ Please Consider

If this project helped you in any way, please consider starring the repository or sharing it with your classmates or friends.
 😊 Thank You!

Feel free to reach out if you need help with deployment, enhancements, or extra features like admin analytics, OTP login, or candidate profile images.

