### ✨ Features ✨  

#### 👤 User Features:  
- **Product Reviews**: Write, edit, delete reviews with instant rating updates.  
- **Wishlist**: Add, remove, and annotate products.  
- **Order Management**: Create orders, view history.  
- **Profile Management**: Manage email, username, addresses.  
- **Shopping Cart**: Add products, adjust quantities, view subtotals.  

#### 👩‍💼 Admin Features:  
- **Product Management**: Add, edit, delete, soft-delete products.  
- **Order Management**: View and update order details/status.  

#### 🔒 Security & UX:  
- **Authentication**: Login, signup, OTP verification, password reset.  
- **UI**: Material UI for a clean experience.  
- **Scalability**: Built for growth.  

### 🚀 Project Setup  

#### 📋 Prerequisites  
- **Node.js**: v21.1.0+  
- **MongoDB**: Installed & running  

#### 📂 Steps to Get Started  
1. **Clone the project**  
   ```sh
   git clone https://github.com/vishalpandey-alf/my-project.git && cd my-project
   ```
2. **Install dependencies**  
   ```sh
   cd frontend && npm install  
   cd ../backend && npm install  
   ```
3. **Set up environment variables**  
   - **Backend (.env)**  
     ```
     MONGO_URI="mongodb://localhost:27017/your-database-name"
     ORIGIN="http://localhost:3000"
     SECRET_KEY="your-secret-key"
     ```
   - **Frontend (.env)**  
     ```
     REACT_APP_BASE_URL="http://localhost:8000"
     ```
4. **Seed the database**  
   ```sh
   cd backend && npm run seed
   ```
5. **Start servers**  
   ```sh
   npm run dev (Backend)  
   cd ../frontend && npm start (Frontend)  
   ```
6. **Demo Login**  
   - **Email**: demo@gmail.com  
   - **Password**: helloWorld@123  

🔗 **Access**:  
- **Backend**: [http://localhost:8000](http://localhost:8000)  
- **Frontend**: [http://localhost:3000](http://localhost:3000)
