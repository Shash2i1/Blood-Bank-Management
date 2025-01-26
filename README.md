# 🩸 Blood Bank Management System

A **Blood Bank Management System** designed to facilitate blood donation, storage, and distribution efficiently.

## 🚀 Features

- **Donor Registration & Management**
- **Blood Inventory Tracking**
- **Blood Request Processing**
- **Hospital & Admin Panel**
- **Secure Authentication & Role-based Access**

## 🛠️ Technologies Used

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Token)
- **Cloud Storage:** Cloudinary (for storing images)

## 📂 Project Structure

```
📦 Blood-Bank-Management
├── 📁 client               # Frontend (React.js)
│   ├── 📁 src
│   ├── 📁 public
├── 📁 server               # Backend (Node.js, Express.js)
│   ├── 📁 models           # Mongoose schemas
│   ├── 📁 routes           # Express API routes
│   ├── 📁 controllers      # Business logic
│   ├── 📁 config           # Database & auth config
│   ├── server.js          # Main server entry point
├── .env                    # Environment variables
├── package.json            # Project dependencies
├── README.md               # Project documentation
└── LICENSE                 # License information
```

## ⚡ Getting Started

### Prerequisites

- Install **Node.js** and **npm**.
- Set up **MongoDB Atlas**.
- Create a **Cloudinary** account for image storage.

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Shash2i1/Blood-Bank-Management.git
   cd Blood-Bank-Management
   ```

2. **Install Dependencies:**
   ```bash
   cd server
   npm install
   cd ../client
   npm install
   ```

3. **Configure Environment Variables:**
   - Create a `.env` file in the **server** folder with:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     CLOUDINARY_CLOUD_NAME=your_cloud_name
     CLOUDINARY_API_KEY=your_api_key
     CLOUDINARY_API_SECRET=your_api_secret
     ```

4. **Start the Application:**
   ```bash
   cd server
   npm start
   ```
   In a new terminal, start the frontend:
   ```bash
   cd client
   npm start
   ```

5. **Access the Application:**
   Open your browser and navigate to `http://localhost:3000`.

## 🎯 Future Enhancements

- **Blood Donation History Tracking**
- **Automated SMS/Email Notifications**
- **AI-Based Blood Demand Prediction**
- **Admin Dashboard for Advanced Analytics**

