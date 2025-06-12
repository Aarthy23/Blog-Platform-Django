# 🚀 Django Tech Blog Platform

This is a dynamic and fully functional blogging web application built using **Django** and **MySQL**. The platform allows users to explore categorized tech content, sign up or log in, create and manage blog posts, comment on others’ posts, and perform advanced tag-based search — all with a smooth and user-friendly interface.

---

## ✨ Features

- 🏠 **Home Page**: Displays featured tech gallery and a list of all user posts.
- 🔐 **Authentication**: Secure sign-up, login, and logout using Django's built-in `User` model.
- 📁 **Categories**: Posts are organized under different technology categories.
- 📝 **User Posts**: Logged-in users can create, edit, or delete their own posts with tags and images.
- 💬 **Commenting System**: Users can comment on each post and manage their own comments.
- 🔍 **Search**: Tag-based search to filter relevant posts.
- 👤 **My Profile**: View all your posts and comments in one place.
- 📧 **HTML Email**: Sends a welcome email on successful registration.
- 🎯 **Access Control**: Only logged-in users can post or comment; users can only modify their own content.

---

## 🛠️ Technologies Used

- **Backend**: Django, Python  
- **Frontend**: HTML, CSS, Javascript  
- **Database**: MySQL  
- **Authentication**: Django User Model  
- **Email Service**: Django Email Backend with HTML templates

---

## 📂 Key Functional Modules

### 1. 🏠 Home Page  
- Tech gallery and all blog posts sorted by latest.

### 2. 🔐 Authentication  
- User registration (with email confirmation), login, logout.

### 3. 📁 Category Browsing  
- Users can view posts by specific categories.

### 4. 📝 Post Creation & Management  
- Create, edit, delete posts.
- Upload images and add tags.

### 5. 💬 Commenting  
- Add, edit, delete comments.
- View all your comments in "My Profile".

### 6. 🔍 Tag Search  
- Search posts by tags dynamically.

### 7. 👤 My Profile  
- Displays your posts and comments in a personalized view.

---

## 📚 What I Learned

- Implementing full CRUD operations in Django.
- Using Django ORM and Models effectively.
- Handling file uploads (images) securely.
- Creating user-specific views using Django’s `@login_required` and `ForeignKey`.
- Using Django's messages framework for user feedback.
- Implementing tag-based filtering and dynamic search.
- Sending HTML emails using Django’s email system.

---

## 🌟 Future Improvements

- Add pagination for long lists of posts.
- Add like/dislike feature for posts and comments.
- Include comment reply/nesting.
- Improve UI with advanced Bootstrap or Tailwind.
- Integrate REST API for post/comment management.
- Add a contact form using Django forms.

---

