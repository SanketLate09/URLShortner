# URL Shortener

## 🚀 Overview
A simple **URL Shortener** built using **Node.js, Express.js, MongoDB**, and **EJS** for the frontend. It allows users to shorten long URLs and access them using a short custom link.

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js
- **Frontend:** EJS
- **Database:** MongoDB (Mongoose ORM)

## 📌 Features
- 🔗 Shorten long URLs
- 🔄 Redirect short URLs to the original links
- 📊 Track the number of clicks on each shortened URL
- 📜 Simple and clean UI with EJS

## 📦 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/Sanketmandwal/URLshortner.git
cd URLshortner
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the project root and add:
```env
PORT=8000
MONGO_URI=your_mongodb_connection_string
BASE_URL=http://localhost:8000
```

### 4️⃣ Start the Server
```sh
npm start
```
The server will start at **http://localhost:8000**.

## 🔥 Usage
1. Enter a long URL in the input field on the homepage.
2. Click the "Generate" button.
3. Get a shortened URL and share it.
4. Click the shortened link to be redirected to the original URL.

## 🗂️ Project Structure
```
📂 url-shortener
 ┣ 📂 views        # EJS templates
 ┣ 📂 public       # Static assets (CSS, JS, images)
 ┣ 📂 models       # Mongoose schemas
 ┣ 📂 routes       # Express routes
 ┣ 📂 controllers  # Business logic
 ┣ 📜 server.js    # Entry point
 ┣ 📜 .env         # Environment variables
 ┣ 📜 package.json # Project dependencies
```

## 📝 API Endpoints
| Method | Endpoint        | Description            |
|--------|----------------|------------------------|
| POST   | `/url`     | Shortens a URL        |
| GET    | `/url/:shortId`  | Redirects to the URL  |
| GET    | `/url/analytics/:shortId`   | Get URL click stats   |

## 🚀 Future Enhancements
- ✅ Custom short URLs
- ✅ QR code generation for short links

## 🤝 Contributing
Feel free to fork this repository, make changes, and submit a pull request!

## 📜 License
This project is licensed under the **MIT License**.

---

💡 **Created with ❤️ by [Sanket Late]**
