# Habit Tracker with Analytics

## Overview

This will be an app that allows users to track their habits, visualize their progress, and receive reminders. It includes features such as user authentication, habit management, data visualization, and notifications.

Project goal is to practise backend technologies: nodejs, postgresql.

## Features Roadmap 

### 1. User Authentication:
- [ ] Allow users to register, log in, and manage their accounts.
- [ ] Implement secure authentication using JWT (JSON Web Tokens).
- [ ] Use **bcryptjs** for password hashing.

### 2. Habit Management:
- [ ] Users can create, update, and delete habits.
- [ ] Set recurring schedules for habits (e.g., daily, weekly).
- [ ] Track completion of habits (e.g., marking a habit as done).
- [ ] Store habit data in a **PostgreSQL** database.

### 3. Data Visualization:
- [ ] Use a charting library to display habit streaks and completion rates.
- [ ] Show analytics like the longest streak, missed days, and success percentage.

### 4. Notifications:
- [ ] Use Expo's notifications API to send reminders for habit completion.

### 5. Backend (Node.js/Express):
- [ ] Build an API to handle habit management.
- Create endpoints for:
  - [ ] User authentication
  - [ ] Habit CRUD operations
  - [ ] Analytics data retrieval
- [ ] Store data in a PostgreSQL database.
- [ ] Use **JWT** for secure authentication.

## Tech Stack

### 1. Frontend:
- **React Native Expo** (TypeScript)
- Hybrid CSS with **Stylesheets** and **TailwindCSS**

### 2. Backend:
- **Node.js** with **Express** for the API (TypeScript)
- **PostgreSQL** as the database

### 3. Other Tools:
- **Postman** for API testing
- **Chart.js** or **Victory** for analytics visualization
- **JWT** for authentication
- **Jest** for backend testing

---
