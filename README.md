🏡 StayNest — Property Listing Web Application
A full-stack property rental platform inspired by Airbnb, built with the MERN-adjacent stack. Users can browse, create, edit, and delete property listings with full authentication, authorization, image uploads, and server-side validation.

Live Demo: [Add your Render/Railway link here]
GitHub: https://github.com/varun47-ch/Property-Listing-Web-Application-Airbnb-clone-

📸 Screenshots
Add screenshots of your homepage, listing page, and login page here

✨ Features
🔐 User Authentication & Authorization — Secure signup/login with Passport.js; route-level access control
🏠 Full CRUD for Listings — Create, view, edit, and delete property listings
🖼️ Cloud Image Uploads — Images stored and served via Cloudinary
✅ Server-side Validation — Input validated using Joi schema before hitting the database
💬 Reviews & Ratings — Users can leave and delete reviews on listings
📱 Responsive UI — Mobile-friendly layout using Bootstrap
🗺️ MVC Architecture — Clean separation of models, views (EJS), and controllers
🔒 Flash Messages — User-friendly success/error notifications
🛠️ Tech Stack
Layer	Technology
Backend	Node.js, Express.js
Templating	EJS (Embedded JavaScript)
Database	MongoDB + Mongoose
Validation	Joi
Authentication	Passport.js (Local Strategy)
Image Storage	Cloudinary + Multer
Frontend Styling	Bootstrap 5, Custom CSS
🚀 Getting Started
Prerequisites
Node.js v18+
MongoDB (local or Atlas)
Cloudinary account (for image uploads)
Installation
# 1. Clone the repo
git clone https://github.com/varun47-ch/Property-Listing-Web-Application-Airbnb-clone-.git
cd Property-Listing-Web-Application-Airbnb-clone-

# 2. Install dependencies
npm install

# 3. Set up environment variables
cp .env.example .env
# Fill in your values (see Environment Variables section)

# 4. Seed the database (optional)
node init/index.js

# 5. Start the server
node app.js
Environment Variables
Create a .env file in the root directory:

ATLASDB_URL=your_mongodb_atlas_connection_string
SECRET=your_session_secret_key
CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
📁 Project Structure
├── controllers/        # Route handler logic (listings, reviews, users)
├── models/             # Mongoose schemas (Listing, Review, User)
├── routes/             # Express routers
├── views/              # EJS templates
│   ├── layouts/
│   ├── listings/
│   └── users/
├── public/css/         # Custom stylesheets
├── utils/              # Error handling utilities
├── init/               # Database seed data
├── middleware.js        # Custom auth & validation middleware
├── schema.js           # Joi validation schemas
├── cloudConfig.js      # Cloudinary configuration
└── app.js              # App entry point
🔮 Upcoming Features
 Booking system with date-range availability
 Payment gateway integration (Razorpay / Stripe)
 Google OAuth login
 Map integration for listing locations
 Admin dashboard
🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

📄 License
This project is open source and available under the MIT License.

👨‍💻 Author
Varun Kumar Chimata
📧 varunkumarchimata47@gmail.com
🔗 LinkedIn | GitHub
