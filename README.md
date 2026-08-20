Live Demo:
[https://your-frontend-url.con](https://user-card-alpha.vercel.app/)

# 👤 User Manager

A modern and responsive **User Management Dashboard** built with **React.js**, **React Hook Form**, and **Tailwind CSS**.

The project is currently focused on building the frontend user-management workflow. More advanced features such as backend integration, database storage, authentication, and API-based operations will be added in future development.

---

## 🚀 Current Features

The following functionality is currently implemented:

* ✅ Create a new user
* ✅ Display users in a responsive card layout
* ✅ Update existing user information
* ✅ Delete users
* ✅ Display total number of users
* ✅ Profile image using image URL
* ✅ Email validation
* ✅ Mobile number validation
* ✅ Profile image URL validation
* ✅ Form error messages
* ✅ Create User form
* ✅ Edit User form
* ✅ Empty state when no users exist
* ✅ Responsive UI
* ✅ Dark-themed dashboard
* ✅ Hover and transition animations
* ✅ Responsive navigation
* ✅ Component-based React architecture

---

## 📝 Current User Form

Currently, users can be created with the following information:

```text
Name
Email
Mobile Number
Profile Image URL
```

The form is handled using **React Hook Form**.

### Current Validation

* Name → Required
* Email → Required + email format validation
* Mobile → Required + 10-character validation
* Profile Image → Required + URL validation

---

## 🔄 Current CRUD Flow

The application currently supports frontend-based CRUD operations:

```text
Create User
     ↓
User added to React State
     ↓
User displayed on Dashboard
     ↓
 ┌───┴────┐
 ↓        ↓
Update   Delete
 ↓        ↓
Updated  Removed
 User     User
```

At the moment, these operations are performed using **React state**.

---

## 🛠️ Tech Stack

### Frontend

* React.js
* JavaScript (ES6+)
* React Hook Form
* Tailwind CSS
* Vite

### React Concepts Used

* `useState`
* Props
* Component composition
* Conditional rendering
* `map()`
* `filter()`
* Event handling
* Form handling
* Form validation

---

## 📂 Project Structure

```text
src/
│
├── components/
│   ├── Form.jsx
│   ├── Navbar.jsx
│   └── Usercard.jsx
│
├── App.jsx
└── main.jsx
```

### Components

**App.jsx**

Main application component responsible for:

* User state
* Edit state
* Dashboard/form switching
* Delete operation
* Update operation
* Rendering user cards

**Form.jsx**

Responsible for:

* Creating users
* Updating users
* Form validation
* Handling form submission

**Usercard.jsx**

Responsible for displaying:

* User image
* User name
* Email
* Mobile number
* Update button
* Delete button

**Navbar.jsx**

Responsible for:

* Application navigation
* Dashboard navigation
* Users navigation
* Create User action

---

## 🎨 UI & Responsive Design

The application currently uses a modern dark dashboard design.

The layout is responsive across different screen sizes:

```text
Mobile        → 1 User Card
Small Screen  → 2 User Cards
Large Screen  → 3 User Cards
XL Screen     → 4 User Cards
```

The UI includes:

* Dark theme
* Responsive layout
* User cards
* Hover effects
* Rounded components
* Form validation states
* Empty state
* Responsive navigation

---

# 🔮 Future Development

The project will gradually evolve from a frontend-only application into a complete **full-stack User Management System**.

### Phase 1 — Data Persistence

* [ ] Add LocalStorage support
* [ ] Preserve users after page refresh
* [ ] Add unique user IDs
* [ ] Improve mobile number validation

### Phase 2 — Backend

* [ ] Build backend API
* [ ] Create REST APIs for users
* [ ] Connect frontend with backend
* [ ] Add proper API error handling
* [ ] Add loading states

### Phase 3 — Database

* [ ] Integrate PostgreSQL / MongoDB
* [ ] Store users permanently
* [ ] Create user database schema
* [ ] Add database CRUD operations

### Phase 4 — Authentication

* [ ] User registration
* [ ] Login system
* [ ] Logout functionality
* [ ] Authentication
* [ ] Authorization
* [ ] Protected routes

### Phase 5 — Advanced User Management

* [ ] Search users
* [ ] Filter users
* [ ] Sort users
* [ ] Pagination
* [ ] User details page
* [ ] Confirmation before deleting users
* [ ] Toast notifications

### Phase 6 — Profile Management

* [ ] Upload profile images
* [ ] Image preview
* [ ] Image storage
* [ ] Profile editing
* [ ] Additional user information

### Phase 7 — Production Ready Application

* [ ] Environment variables
* [ ] Secure API configuration
* [ ] Form-level server validation
* [ ] Better error handling
* [ ] Performance optimization
* [ ] Deployment
* [ ] Production database
* [ ] CI/CD

---

## 🗺️ Development Roadmap

```text
Frontend UI
    ↓
React State Management
    ↓
Form Validation
    ↓
CRUD Operations
    ↓
LocalStorage
    ↓
Backend API
    ↓
Database
    ↓
Authentication
    ↓
Advanced User Management
    ↓
Production Deployment
```

---

## 📌 Project Status

**Current Status:** 🟢 Frontend Development

The basic user-management functionality has been implemented using React state.

Backend, database, authentication, persistent storage, and advanced management features are planned for future versions.

---

## 🎯 Purpose of the Project

This project is being developed as a practical React application to understand how a frontend application evolves from a simple UI into a complete full-stack application.

The project will progressively introduce:

**React → State Management → API → Backend → Database → Authentication → Production**

---

## 👨‍💻 Author

**Rajat**

A practical React.js project focused on learning and implementing modern frontend and full-stack development concepts.

---

## 📄 License

This project is created for learning and educational purposes.
