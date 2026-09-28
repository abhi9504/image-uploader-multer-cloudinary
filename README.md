# 📸 Image Uploader - Multer & Cloudinary

A full-stack image uploading application built with **Node.js, Express.js, MongoDB, Multer, and Cloudinary**.

This project allows users to upload images through a web interface. Uploaded images are processed using **Multer** and stored securely using **Cloudinary**, while MongoDB is used for database connectivity.

---

## 🚀 Features

- 📤 Upload images through a web interface
- ☁️ Store images using Cloudinary
- 📁 Handle file uploads using Multer
- 🗄️ MongoDB database integration
- ⚡ Express.js backend
- 🎨 EJS-based frontend
- 🔐 Environment variables for sensitive credentials
- 📱 Simple and responsive user interface
- 🛡️ `.env` and `node_modules` protected using `.gitignore`

---

## 🛠️ Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### File Upload & Storage
- Multer
- Cloudinary

### Frontend
- HTML
- CSS
- EJS

### Development Tools
- Nodemon
- Git
- GitHub

---

## 📂 Project Structure

```text
Image-Uploader-Multer-Cloudinary/
│
├── public/
│   └── uploads/
│
├── views/
│   └── index.ejs
│
├── .env
├── .gitignore
├── package.json
├── package-lock.json
└── server.js

⚙️ Installation & Setup
1. Clone the Repository
git clone https://github.com/abhi9504/image-uploader-multer-cloudinary.git
2. Navigate to the Project
cd image-uploader-multer-cloudinary
3. Install Dependencies
npm install
🔐 Environment Variables

Create a .env file in the root directory:

PORT=1000

MONGODB_URI=your_mongodb_connection_string

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

⚠️ Never upload your .env file to GitHub.
Make sure .env is included in .gitignore.

▶️ Run the Project
Development Mode
npm run dev

Or, if Nodemon is not configured in package.json:

npx nodemon server.js
Normal Mode
node server.js

The application will run on:

http://localhost:1000
📤 How It Works

The image upload process follows these steps:

User
  ↓
Select Image
  ↓
Express.js Server
  ↓
Multer
  ↓
Cloudinary
  ↓
Image Storage
  ↓
MongoDB
User selects an image from the frontend.
The image is sent to the Express.js server.
Multer handles the uploaded file.
Cloudinary stores the image.
MongoDB can be used to store related image information.
The application returns the result to the user.
📸 Screenshots

Add your project screenshots here.

For example:

![Image Uploader](screenshots/image-uploader.png)

Create a folder in your project:

screenshots/
└── image-uploader.png

Then place your screenshot inside this folder and push it to GitHub.

🔒 Security

Sensitive information such as:

MongoDB connection strings
Cloudinary API keys
Cloudinary API secrets
Other credentials

should always be stored in environment variables.

Example:

CLOUDINARY_API_SECRET=your_secret

Never hard-code these credentials directly into your source code.

📦 Main Dependencies

The project uses packages such as:

express
mongoose
multer
cloudinary
dotenv
ejs

Install all dependencies using:

npm install
🎯 Learning Objectives

This project helped me understand:

Building REST APIs with Express.js
Handling multipart/form-data
File uploading with Multer
Cloud-based image storage with Cloudinary
MongoDB integration with Mongoose
Using environment variables
Structuring a Node.js backend
Git and GitHub workflow
🔮 Future Improvements
👤 User authentication
🖼️ Image gallery
🗑️ Delete uploaded images
✏️ Image metadata management
📏 Image size and type validation
🔗 Shareable image URLs
📱 Improved responsive UI
🚀 Deployment on platforms such as Render or Railway
👨‍💻 Author

Abhishek Kumar

B.Tech Computer Science Engineering Student

GitHub:
https://github.com/abhi9504

⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

📄 License

This project is created for learning and educational purposes.


### 📸 Screenshot kaha rakhna hai?

Tumhare project ke root folder me ek folder banao:

```text
Lecture_17_Project_2
│
├── public
├── views
├── screenshots
│   └── image-uploader.png
├── server.js
├── package.json
└── .gitignore

![Image Uploader](screenshots/image-uploader.png)
<img width="1890" height="958" alt="image" src="https://github.com/user-attachments/assets/c74f3127-ca44-40cf-b6ac-2840c5e7e864" />

## 📸 Application Screenshot

Here is a preview of the Image Uploader application:

![Image Uploader Application](screenshots/image-uploader.png)
<img width="1900" height="955" alt="image" src="https://github.com/user-attachments/assets/d651d3b2-4336-47ef-8b0f-8098358e4b9e" />

