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

⚙️ **How to Run Locally**
Follow these steps to run Garden Tribe on your local machine:

# 1. Clone the repo
git clone https://github.com/your-username/garden-tribe.git

# 2. Navigate into the project directory
cd garden-tribe

# 3. Install dependencies
npm install

# 4. Create a .env file and add necessary environment variables
REACT_APP_apiKey=your_firebase_api_key
REACT_APP_authDomain=...
REACT_APP_projectId=...
REACT_APP_storageBucket=...
REACT_APP_messagingSenderId=...
REACT_APP_appId=...

# 5. Start the app
npm start
## 🔗 Live Website
👉 [Visit BlogNest](https://blog-nest-a9329.web.app/)
