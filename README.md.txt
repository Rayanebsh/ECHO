===========================
     ECHO PLATFORM
===========================

ECHO is a social-academic web platform designed for the ESTIN community. It fosters communication between students, teachers, and administrators through features like posts, messaging, academic claims, announcements, and more.

---------------------------
🔧 INSTALLATION & SETUP
---------------------------

1. Clone the repository

   git clone your-repo-url
   cd echo

2. Install dependencies

   # Frontend
   cd client
   npm install

   # Backend
   cd ..server
   npm install

3. Create the `.env` file in the `server` directory with the following content

   ---------------------
   📄 .env configuration
   ---------------------

PORT=5000
NODE_ENV=development

# MongoDB Connection
 MONGODB_URI=


# JWT Secret
JWT_SECRET=meow
JWT_EXPIRES_IN=7d

# Email Configuration (Nodemailer)
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_USER=
EMAIL_PASS=
EMAIL_FROM=


# File Upload Paths
UPLOAD_PATH=./uploads

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
GOOGLE_CALLBACK_URL=
FRONTEND_URL=http://localhost:5000


SESSION_SECRET=

4. (Optional) Create a `.env` file in the `client` directory if you use environment variables in the frontend

   VITE_API_URL=httplocalhost5000

---------------------------
🚀 RUNNING THE APPLICATION
---------------------------

In two separate terminal windows or tabs

   # Start the backend
   cd server
   npm run dev

   # Start the frontend
   cd client
   npm run dev

By default
- Backend runs on httplocalhost5000
- Frontend runs on httplocalhost5173

---------------------------
👨‍💻 TEAM MEMBERS
---------------------------
- Macyl MOUMOU (Team Leader)
- Rayane Bessah
- Souhail Lounissi
- Ikram Khaled
- Sara OUELLABI
- Omar Fakhreddine Aoughlis

Frontend Souhail, Ikram, Sara  
Backend Macyl, Rayane, Omar

---------------------------






