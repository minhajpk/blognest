# 📝 BlogNest – A Modern Blogging Web App
A full-featured blog web application where users can sign up, create posts, and read blogs in real-time. It supports dynamic content rendering, user authentication, and mobile responsiveness.

## 🌟 Main Features
- 🔐 User authentication (Sign in/up via Firebase)
- ✍️ Rich text editor for posting blogs (Jodit Editor)
- 📄 Blog create, update, delete, and read functionality (CRUD)
- 👤 User-specific article management
- 📈 Blog statistics with author-based filtering
- 💬 Commenting system (with optional moderation)
- 🌐 Responsive layout for all devices

## 🧰 Technologies Used

| Technology       | Version     | Purpose                      |
|------------------|-------------|------------------------------|
| React.js         | ^18.x       | Frontend framework           |
| Firebase         | ^9.x        | Authentication & hosting     |
| Node.js          | ^18.x       | Backend runtime (if used)    |
| Express.js       | ^4.x        | Backend API handling         |
| MongoDB (Atlas)  | Cloud       | Database                     |
| Jodit Editor     | ^1.x        | Rich text blog editor        |
| React Router DOM | ^6.x        | Client-side routing          |
| Tailwind CSS     | ^3.x        | UI styling                   |

## 📦 Project Dependencies

```bash
"react"
"react-dom"
"react-router"
"firebase"
"tailwindcss"
"daisyui"
"react-icons"
"react-toastify"
```

---

## ⚙️ How to Run Locally

Follow these steps to run **Blog Nest** on your local machine:

```bash
# 1. Clone the repo
git clone https://github.com/your-username/blog-nest.git

# 2. Navigate into the project folder
cd blog-nest

# 3. Install dependencies
npm install

# 4. Add Firebase config in .env file
REACT_APP_apiKey=your_firebase_api_key
REACT_APP_authDomain=your_auth_domain
REACT_APP_projectId=your_project_id
REACT_APP_storageBucket=your_storage_bucket
REACT_APP_messagingSenderId=your_sender_id
REACT_APP_appId=your_app_id

# 5. Run the development server
npm start
```

## 🔗 Live Website
👉 [Visit BlogNest](https://blog-nest-a9329.web.app/)
