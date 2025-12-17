🚀 About This Repository
This repository is primarily used for testing the git push functionality with GitHub and automating the build process to generate a dist (distribution) folder for deployment.

The generated dist folder can be hosted using Apache (2.4), making it suitable for testing and deploying the frontend of a MERN stack application.

🔧 Note: This version may contain slight code differences compared to the main testing branch, as it includes deployment-specific adjustments and configurations.

# MERN_Project

A modern, real-time chat application built with the **MERN stack** (MongoDB, Express.js, React, Node.js) and **Socket.IO** for instant messaging.

![MERN_Project]()
<!-- Replace with your own screenshot or GIF -->

🔗 **Live Demo**:  
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/08294500-ca46-48c9-996f-b801b7b243c2" />
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/fe4c9f39-d7ab-4f02-bfbc-3967d1af2e24" />
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/7875c6c9-c61c-441c-a553-776ad470b88b" />
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/417cda8e-d5b1-45f8-aeb3-4ab80de45e5b" />
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/9ae5cb15-609c-48c7-b723-23ebb4c00b58" />
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/c66f2d61-72f2-4e1d-9626-aa6a68712599" />
![Untitled video - Made with Clipchamp](https://github.com/user-attachments/assets/cbaa5f5d-7149-4d6e-936e-2d4162dde8f7)
![Untitled video - Made with Clipchamp (1)](https://github.com/user-attachments/assets/d0ee0bdc-7778-413c-a66e-cbee3aacca14)
<img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/05e53f65-87ba-442e-a000-d8f367b96e31" />


🔗 **Backend API**: 

## ✨ Features

- Real-time messaging with **Socket.IO**
- One-on-one private chat
- Online/Offline user status
- User authentication (JWT + bcrypt)
- Responsive design (Mobile & Desktop friendly)
- Clean and intuitive UI with Tailwind CSS
- Profile picture upload
- Notifications for new messages

## 🛠 Tech Stack

### Frontend
- React.js (Vite / Create React App)
- React Router DOM
- Socket.IO Client
- Axios
- Tailwind CSS
- Context API or Redux Toolkit (for state management)

### Backend
- Node.js + Express.js
- MongoDB + Mongoose
- Socket.IO
- JWT Authentication
- bcryptjs for password hashing
- Cloudinary / AWS S3 for image uploads (optional)

### Tools & Libraries
- dotenv
- cors
- express-async-handler
- cloudinary (for file uploads)

##🚀 Quick Start
Prerequisites
Node.js (v16+)
MongoDB (local or MongoDB Atlas)
npm or yarn
Installation
Clone the repo:

bash
git clone https://github.com/your-username/MERN_Project.git
cd MERN_Project

Create a .env file inside the backend/ folder:

env
MONGODB_URI=your_mongodb_uri
PORT=5001
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
NODE_ENV=development

Install dependencies:

bash
cd backend && npm install
cd ../frontend && npm install

Run the app locally:

bash
# In backend/
npm run dev

# In frontend/
npm run dev

🙏 Special Thanks
Thanks to @codesistency for the detailed walkthrough and inspiration.
📺 Watch the original YouTube tutorial

Honor and credit go to @codesistency for the chat app demo and implementation guide.
