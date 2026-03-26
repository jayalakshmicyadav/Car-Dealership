# Online Car Dealership (MERN Stack)

A full-stack web application that simplifies the car buying process by allowing users to browse, compare, and interact with dealers in real-time.

---

## 🌟 Features

### 💬 Buyer–Dealer Interaction
- Direct communication between buyers and dealers  
- Helps users clarify details and make informed decisions  

### 🤝 Live Chat & Negotiation
- Real-time chat using Socket.io  
- Users can negotiate prices and deals directly  

### 💰 Best Price Guarantee
- Competitive pricing on all cars  
- Find a lower price? Get 100% refund of the difference  

### 🎯 Personalized Service
- Recommendations based on user preferences  
- Guided support throughout the buying process  

### 🕒 24/7 Customer Support
- Round-the-clock assistance for users  

---

## 🏗️ Tech Stack

Frontend:
- React.js
- Axios

Backend:
- Node.js
- Express.js

Database:
- MongoDB

Other:
- Socket.io (Real-time chat)
- JWT Authentication
- ImageKit / Cloudinary

---

## ⚙️ Installation & Setup

### 1. Clone Repository
git clone https://github.com/your-username/car-dealership.git
cd car-dealership

---

### 2. Backend Setup
cd backend
npm install

Create .env file:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
IMAGEKIT_PUBLIC_KEY=your_key
IMAGEKIT_PRIVATE_KEY=your_key
IMAGEKIT_URL_ENDPOINT=your_url

Run backend:
npm start

---

### 3. Frontend Setup
cd frontend
npm install
npm start

---

## 🔄 Workflow

- User interacts with React frontend  
- API requests sent to Node.js backend  
- Backend processes logic using Express  
- Data stored/retrieved from MongoDB  
- Response sent as JSON  
- UI updates dynamically  
- Socket.io enables real-time chat & negotiation  

---

## 🚀 Deployment

### Backend (Render / Railway)
1. Push code to GitHub  
2. Create new service on Render/Railway  
3. Add environment variables  
4. Deploy  

### Frontend (Vercel)
1. Import repo in Vercel  
2. Select frontend folder  
3. Deploy  

---

## 🔐 Security

- JWT Authentication  
- Role-based access (Buyer / Dealer)  
- Password protection  

---

## 📌 Future Enhancements

- Payment integration  
- AI recommendations  
- Advanced filters  
- Mobile app  

---

## 👨‍💻 Author

Your Name  
GitHub: https://github.com/your-username
