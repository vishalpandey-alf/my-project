✨ Features ✨

👤 User Features:

🖋️ Product Reviews:

Write, edit, and delete reviews.

Instant updates on ratings and star percentages.

❤️ Wishlist:

Add, remove, and annotate products with personalized notes.

📦 Order Management:

Create new orders and view order history.

👤 Profile Management:

Manage email, username, and multiple addresses.

🛒 Shopping Cart:

Add products, adjust quantities, and view subtotals.

👩‍💼 Admin Features:

🔧 Product Management:

Add, edit, delete, and soft-delete products.

Manage product attributes like name and stock.

📁 Order Management:

View and update order details and status.

🔒 Security & User Experience:

🔐 Secure Authentication:

Login, signup, OTP verification, password reset, and logout.

🎨 Intuitive Interface:

Powered by Material UI for a visually appealing and user-friendly experience.

📈 Scalability:

Built for growth, with a scalable architecture to handle increasing user demands.

🚀 Project Setup

📋 Prerequisites

Node.js: Version v21.1.0 or later

MongoDB: Installed and running locally

📂 Steps to Get Started

1. Clone the project:

git clone https://github.com/vishalpandey-alf/my-project.git
cd my-project

2. Install dependencies for both frontend and backend:

Frontend:

cd frontend
npm install

Backend:

cd ../backend
npm install

3. Configure environment variables:

Backend:
Create a .env file in the backend directory with the following:

MONGO_URI="mongodb://localhost:27017/your-database-name"
ORIGIN="http://localhost:3000"
✨ Features ✨

👤 User Features:

🖋️ Product Reviews:

Write, edit, and delete reviews.

Instant updates on ratings and star percentages.

❤️ Wishlist:

Add, remove, and annotate products with personalized notes.

📦 Order Management:

Create new orders and view order history.

👤 Profile Management:

Manage email, username, and multiple addresses.

🛒 Shopping Cart:

Add products, adjust quantities, and view subtotals.

👩‍💼 Admin Features:

🔧 Product Management:

Add, edit, delete, and soft-delete products.

Manage product attributes like name and stock.

📁 Order Management:

View and update order details and status.

🔒 Security & User Experience:

🔐 Secure Authentication:

Login, signup, OTP verification, password reset, and logout.

🎨 Intuitive Interface:

Powered by Material UI for a visually appealing and user-friendly experience.

📈 Scalability:

Built for growth, with a scalable architecture to handle increasing user demands.

🚀 Project Setup

📋 Prerequisites

Node.js: Version v21.1.0 or later

MongoDB: Installed and running locally

📂 Steps to Get Started

1. Clone the project:

git clone https://github.com/vishalpandey-alf/my-project.git
cd my-project

2. Install dependencies for both frontend and backend:

Frontend:

cd frontend
npm install

Backend:

cd ../backend
npm install

3. Configure environment variables:

Backend:
Create a .env file in the backend directory with the following:

MONGO_URI="mongodb://localhost:27017/your-database-name"
ORIGIN="http://localhost:3000"
EMAIL="your-email@example.com"
PASSWORD="your-email-password"
LOGIN_TOKEN_EXPIRATION="30d"
OTP_EXPIRATION_TIME="120000"
PASSWORD_RESET_TOKEN_EXPIRATION="2m"
COOKIE_EXPIRATION_DAYS="30"
SECRET_KEY="your-secret-key"
PRODUCTION="false"

Frontend:
Create a .env file in the frontend directory with the following:

REACT_APP_BASE_URL="http://localhost:8000"

4. Seed the database with sample data:

cd backend
npm run seed

5. Start development servers:

Backend:

npm run dev

Frontend:

cd ../frontend
npm start

6. Login with the demo account:

Email: demo@gmail.com  
Password: helloWorld@123

🔗 Access the Application

Backend: http://localhost:8000

Frontend: http://localhost:3000
