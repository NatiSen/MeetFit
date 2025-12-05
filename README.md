<div align="center">
<img src="src/front/assets/img/logofooter.png" alt="MeetFit Logo" width="150"/>
  <h1 style="color:#FF6B6B; font-family:'Poppins', sans-serif;">MeetFit</h1>


  Sport • Connect • Explore

  Social Sport App
  
 <br>
</div>
MeetFit is an application designed to connect people through sports.
It allows users to search, create, and join sport activities nearby — from running, yoga, and fitness to climbing, cycling, or team sports.

MeetFit helps active individuals to:

- find workout partners,

- stay motivated,

- discover new ways to be active,

- build connections based on shared interests.

We believe that exercising is easier, more enjoyable, and more motivating when you do it with others.
MeetFit exists to bring people together through movement, community, and shared sports experiences.

<br>
<hr style="height: 1px;border:none;background-color:#FF6B6B;margin:20px 0;" />
<br>

## Key Features

✔️ Robust Architecture: Full-stack application powered by React + Flask, delivering fast, reliable performance.

✔️ Interactive Map: Google Maps integration to explore, create, and join activities around you.

✔️ User System: Complete authentication flow with login, registration, password recovery, JWT protection, and editable user profiles.

✔️ Activity Management: Create events, join others, manage your own activities, view joined activities, and track ratings.

✔️ Activity Ratings: Interactive 1–5 star rating system with personalized feedback tools.

✔️ Modern UI: Neon-style design, dynamic quotes, animated splash screens, responsive components, and toast notifications.

✔️ Fully Responsive: Optimized for mobile, tablet, and desktop experiences.


<hr style="border: 2px solid #E3FE18;">
<br>

## Technologies Used

### ❀  Frontend

- ⚛️ React.js — Components, routing, and UI architecture
- 🌍 Google Maps API — Real-time interactive map
- 🎨 CSS3 / Custom UI — Neon styles, responsive layouts
- 🔔 React Toastify — Notifications
- 📦 Context / Local State — State management
- 🔧 Vite — Fast development server

### ❀  Backend

- 🐍 Python — Server logic
- 🌐 Flask — Routing, authentication, mailing
- 🗄️ SQLAlchemy — Database ORM
- 💾 PostgreSQL — Storage for users, activities, ratings
- 🔐 JWT — Secure authentication
- ✉️ Flask-Mail — Password recovery emails
- 🗺️ Google Maps integration — Coordinates-based events

### ❀  State & Data Management

- Global state via React (store.js)
- Custom API services (auth.js, user.js, activity handlers)
- Live updates on new activities
  

<hr style="border: 2px solid #E3FE18;">
<br>

## Core Components

🔐 Authentication & User System

- User registration & login
- Forgot password (email)
- Password reset with secure token
- JWT authentication
- Protected routes
- User profile view (User.jsx)
- Edit user details (UpdateUser.jsx)
- AuthShell — consistent layout for auth pages

🗺️ Interactive Map (Google Maps API)

- Powered by @react-google-maps/api.
- Shows all nearby sport activities
- Click on the map to create a new event
- Markers with InfoWindows showing event details
- Automatic user geolocation
- Animated onboarding tips (first-time help)
- Real-time updating after event creation

🤸 Activities System

- Create new sport activities
- Choose title, sport, description, location, max participants, date
- Join or leave activities
- View joined or created events
- Live reload after event changes
- Fallback events when backend is offline
- Activity rating system (1–5 stars)
- Dynamic sport icons & images

✨ UI & Experience

- Home splash screen
- Motivational quotes system
- Modern neon-style UI components
- Toast notifications for all actions
- ScrollToTop navigation
- Dual navigation bars:
- Public Navbar
- Internal Navbar (after login)

<br>

## Planned Features
💭 Real-time Chat
- Live chat inside each activity using WebSockets / Socket.io.

👥 Follow System
- Follow users, get social recommendations, see friends’ activities.

🛎️ Push Notifications
 - Event reminders
 - Followers
 - Joins
 - Activity changes

<hr style="border: 2px solid #E3FE18;">
<br>

## 🔗 Check it out!

