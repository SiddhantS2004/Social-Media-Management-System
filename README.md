# Social-Media-Management-System
# 📝 Project Overview

The objective of this project is to design and implement a Database Management System (DBMS) that effectively manages social media accounts and their associated activities. This system aims to store and monitor user-generated content, user interactions, and engagement patterns across a social platform.

---

## 🎯 Features

### 🔐 User Management
- Add, delete, and update user profiles  
- Manage follower-following relationships

### 🖼️ Content Tracking
- Store posts, images, videos  
- Record timestamps and content type

### ❤️ Interaction Tracking
- Track likes, comments, and shares on posts  
- Maintain comment threads and share origins

### 📈 Engagement Insights
- Most liked/commented/shared posts  
- Identify most active periods (hour/day/week)  
- Analyze follower growth and post reach

### 🔄 User Interactions
- View engagement between specific users  
- Discover common followers or mutual activity

---

## 🗃️ Database Schema Overview

**Main Tables:**
- `Users` – stores user profiles  
- `Posts` – stores post details  
- `Likes` – tracks likes per post per user  
- `Comments` – stores comments and their replies  
- `Shares` – tracks shared posts  
- `Followers` – handles follower/following relationships  
- `Saves` – tracks who saved posts when

---

## 🛠️ Tech Stack

- **Database:** PostgreSQL
