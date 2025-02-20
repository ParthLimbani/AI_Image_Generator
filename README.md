# AI Image Generator (MERN Stack)

![AI Image Generator](https://img.shields.io/badge/MERN-Stack-green.svg)
![OpenAI API](https://img.shields.io/badge/OpenAI-API-blue.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 🚀 Overview

AI Image Generator is a full-stack web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It leverages OpenAI's API to generate high-quality AI-driven images based on user prompts.

## 🎨 Features

- Generate images using AI based on text prompts
- Responsive and modern UI with React
- Secure backend with JWT authentication

## 🛠 Tech Stack

### Frontend
- React.js (Vite or Create React App)
- Tailwind CSS for styling
- React Router for navigation

### Backend
- Node.js with Express.js
- MongoDB with Mongoose
- OpenAI API for image generation
- Cloudinary (optional) for image storage
- JWT for authentication

## 📦 Installation

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/ParthLimbani/AI_Image_Generator.git
cd AI_Image_Generator
```

### 2️⃣ Install Dependencies
#### Backend
```sh
cd server
npm install
```
#### Frontend
```sh
cd client
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the `server` directory and add:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key
CLOUDINARY_CLOUD_NAME=your_cloud_name (if using Cloudinary)
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 4️⃣ Run the Application
#### Backend
```sh
cd server
npm start
```
#### Frontend
```sh
cd client
npm start
```

## 🚀 Usage
1. Sign up or log in to the application.
2. Enter a text prompt and click the "Generate Image" button.
3. The AI will generate an image based on the prompt.
4. Save or download the generated image.

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit a pull request.

## 📬 Contact
For any inquiries or feedback, feel free to reach out:
- **GitHub**: [ParthLimbani](https://github.com/ParthLimbani)
- **Email**: parthlimbani19@example.com

