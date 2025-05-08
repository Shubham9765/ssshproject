# Online Form Filling Service

A web application for online form filling services including government job vacancies, shop act, and other services.

## Features

- User Authentication (Sign Up/Login)
- Admin Dashboard
- Service Selection
- Work Status Tracking
- Advertisement Management
- Form Filling Services

## Project Structure

```
├── index.html              # Main landing page
├── user/
│   ├── login.html         # User login page
│   ├── signup.html        # User registration page
│   ├── dashboard.html     # User dashboard
│   └── services.html      # Available services
├── admin/
│   ├── login.html         # Admin login page
│   └── dashboard.html     # Admin dashboard
├── css/
│   ├── style.css         # Main stylesheet
│   ├── user.css          # User-specific styles
│   └── admin.css         # Admin-specific styles
├── js/
│   ├── config.js         # Supabase configuration
│   ├── auth.js           # Authentication functions
│   ├── user.js           # User-specific functions
│   └── admin.js          # Admin-specific functions
└── assets/               # Images and other assets
```

## Setup Instructions

1. Clone the repository
2. Create a Supabase project and get your project URL and anon key
3. Update the Supabase configuration in `js/config.js`
4. Open `index.html` in your browser

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Supabase (Backend & Authentication) 