# AI-Based Automated Defective Exhibit Identification System

This project allows users to upload multiple images to a backend server, where they are stored and processed.

## Features
- Supports multiple file uploads
- Displays selected files before uploading
- Provides feedback on successful or failed uploads
- Backend built with **Node.js, Express, and Multer**
- Frontend built with **React**

---

## **Installation & Setup**

### **1. Clone the Repository**
```sh
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### **2. Setup the Backend**

#### **Install Dependencies**
```sh
cd backend
npm install
```

#### **Run the Server**
```sh
node server.js
```
The backend will start on **http://localhost:5000**

### **3. Setup the Frontend**

#### **Install Dependencies**
```sh
cd frontend
npm install
```

#### **Run the React App**
```sh
npm start
```
The frontend will start on **http://localhost:3000**

---

## **Usage**
1. Open `http://localhost:3000` in your browser.
2. Click the file input and select images to upload.
3. Click the **Upload** button.
4. Wait for the confirmation message.

---

## **Project Structure**
```
├── backend
│   ├── server.js      # Express server with Multer for uploads
│   ├── uploads/       # Stores uploaded images
│   ├── package.json   # Backend dependencies
│
├── frontend
│   ├── src/
│   │   ├── App.js     # React frontend for file upload
│   │   ├── App.css    # Styles
│   ├── package.json   # Frontend dependencies
│
├── README.md          # Documentation
```

---

## **Troubleshooting**
### "Uploads folder not found" error
- Ensure that the `uploads/` directory exists in the backend folder. If not, the backend will create it automatically.

### "CORS policy" error
- Ensure that the frontend is correctly pointing to `http://localhost:5000` and the backend has `cors` enabled.

---

## **License**
This project is open-source and available under the **MIT License**.

---

## **Contributing**
Feel free to fork this project and submit pull requests to improve it!

