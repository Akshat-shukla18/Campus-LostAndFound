# 🎒 Campus Lost & Found Portal

### Reconnecting People with Their Belongings Through Community Collaboration
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/409ddc4e-8042-47b4-807f-c86a5810f181" />


Campus Lost & Found Portal is a full-stack MERN application designed specifically for college campuses to help students, faculty, and staff report lost or found items through an interactive social-feed-based system.

Users can create posts about lost or found belongings, browse campus-wide reports, communicate with item owners or finders, and contribute to a transparent and organized lost-and-found ecosystem.

---
# 🚀 Overview

Every year, students lose valuable items such as:

* Wallets
* ID Cards
* Laptops
* Mobile Phones
* Keys
* Water Bottles
* Books
* Earbuds
* Chargers
* Bags

Traditional lost-and-found systems are often disconnected, slow, and difficult to access.

The Campus Lost & Found Portal provides a centralized digital platform where users can instantly report lost or found items, making recovery faster and more efficient.

---

# ✨ Features

## 👤 User Authentication

* Secure Registration & Login
* JWT Authentication
* Protected Routes
* User Profiles

---

## 📢 Interactive Lost & Found Posts

Users can create posts for:

### 🔴 Lost Items

Report belongings that have been misplaced.

### 🟢 Found Items

Report items that have been discovered.

Each post contains:

* Item Name
* Description
* Images
* Location
* Date & Time
* Contact Information
* Item Category

---

## 📰 Community Feed

A centralized feed displaying:

* Recent Lost Items
* Recent Found Items
* Trending Reports
* Latest Activity

Users can quickly browse reports and identify matching items.

---

## 🔍 Smart Search & Filtering

Filter reports by:

* Item Category
* Lost/Found Status
* Date
* Location
* Keywords

Search functionality helps users locate relevant reports quickly.

---

## 💬 User Communication

Users can connect with each other regarding reported items.

Features include:

* Direct Messaging
* Contact Information Sharing
* Recovery Coordination

---

## 📊 Dashboard Analytics

Track campus activity through:

* Daily Lost Items
* Daily Found Items
* Monthly Statistics
* Recovery Success Rate
* Recent Reports

---

## ⭐ User Reputation System

Users who help return lost belongings can receive:

* Ratings
* Appreciation Scores
* Community Recognition

This encourages positive participation across the campus community.

---

# 🎯 Problem Statement

Students frequently lose personal belongings on campus, and existing recovery methods often rely on notice boards, social media groups, or word-of-mouth communication.

This creates challenges such as:

* Delayed reporting
* Limited visibility
* Lost recovery opportunities
* Fragmented communication

The Campus Lost & Found Portal provides a centralized digital solution that increases visibility, promotes community engagement, and improves recovery rates.

---

# 🛠 Technology Stack

## Frontend

* React.js
* HTML5
* CSS3
* JavaScript

## Backend

* Node.js
* Express.js

## Database

* MongoDB

## Authentication

* JWT
* bcrypt.js

## File Uploads

* Multer
* Cloudinary

## Deployment

* Render
* Vercel
* Railway

---

# 📂 Project Structure

```bash
Campus-Lost-Found/
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── styles/
│   │
│   └── public/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── uploads/
│   └── server.js
│
├── .env
└── README.md
```

---

# 🔄 Workflow

### Lost Item Scenario

1. Student loses an item.
2. Creates a Lost Post.
3. Post appears on the community feed.
4. Other users view the post.
5. Finder contacts the owner.
6. Item is recovered.
7. Post is marked as Resolved.

---

### Found Item Scenario

1. User finds an item.
2. Creates a Found Post.
3. Item appears in Found Feed.
4. Owner identifies the item.
5. Communication is established.
6. Item is returned.
7. Post is marked as Recovered.

---

# 📱 Core Modules

## Authentication Module

* Registration
* Login
* User Management

## Post Management Module

* Create Post
* Edit Post
* Delete Post
* Upload Images

## Feed Module

* Lost Feed
* Found Feed
* Recent Activity

## Search Module

* Search Reports
* Filter Reports

## Communication Module

* Messaging
* Notifications

## Recovery Module

* Mark as Recovered
* Feedback System

---

# 🌟 Key Highlights

✅ Full-Stack MERN Architecture

✅ Interactive Social Feed

✅ Lost & Found Post System

✅ Image Upload Support

✅ Real-Time Community Visibility

✅ Search & Filter Functionality

✅ Recovery Tracking

✅ Campus-Focused Solution

✅ Fully Deployable

---

# 📈 Impact

The platform creates a connected campus community where students actively help one another recover lost belongings.

Benefits include:

* Faster item recovery
* Reduced dependency on physical notice boards
* Increased community participation
* Better campus organization
* Transparent reporting process

---

# 🔮 Future Enhancements

* AI-powered item matching
* Image recognition for similar objects
* QR code integration for student belongings
* Real-time notifications
* Mobile application
* Chat system with Socket.io
* Campus map integration
* Admin moderation dashboard

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/campus-lost-found.git
```

## Install Dependencies

### Backend

```bash
cd backend
npm install
```

### Frontend

```bash
cd frontend
npm install
```

## Configure Environment Variables

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_URL=your_cloudinary_url
```

## Start Backend

```bash
npm start
```

## Start Frontend

```bash
npm start
```

---

# 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests for new features, improvements, or bug fixes.

---

# 📄 License

Licensed under the MIT License.

---

# 👨‍💻 Developer

Developed using the MERN Stack to create a smart, community-driven solution for lost and found item management within educational institutions.

### 🎒 Lost Something? Found Something? Let the Community Help.
