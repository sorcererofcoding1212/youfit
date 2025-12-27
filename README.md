# Youfit

A full-stack fitness tracking application designed to help users plan workouts,
track progress, and improve performance over time.

---

## Overview

Youfit is a full-stack web application that allows users to log exercises,
organize workout routines, and analyze their fitness progress through
interactive visualizations.

The application focuses on simplicity, flexibility, and clarity, enabling
users to build consistent workout habits while gaining meaningful insights
into their performance.

This repository serves as the **central documentation and entry point**
for the Youfit project.

---

## Links

- Live Application: https://youfit-frontend.netlify.app
- Frontend Repository: https://github.com/sorcererofcoding1212/youfit-frontend
- Backend Repository: https://github.com/sorcererofcoding1212/youfit-backend

---

## Key Features

- **Authentication**  
  Secure in-house authentication using JWT-based cookies.

- **Exercise Logging**  
  Users can create, edit, and delete exercises to monitor and improve workout performance.

- **Workout Routines**  
  Custom routines allow users to group exercises for easier planning and
  more efficient workout tracking.

- **Analytics & Insights**  
  Interactive charts and analytics help users visualize progress
  and track fitness goals over time.

- **Responsive UI**  
  Fully responsive interface with smooth and intuitive user feedback.

---

## Tech Stack

### Frontend
- React
- TypeScript
- Tailwind CSS
- Shadcn UI
- Recharts

### Backend
- Node.js
- Express
- TypeScript
- Mongoose

### Database
- MongoDB

---

## Architecture Overview

Youfit follows a client–server architecture where the frontend communicates
with the backend through RESTful APIs.

The backend handles authentication, business logic, and data persistence,
while the frontend focuses on user experience, state management, and data
visualization.

MongoDB is used to support flexible data modeling for workouts, routines,
and user-specific tracking needs.

---

## Repository Structure

The frontend and backend are maintained in **separate repositories** to enable
independent development and deployment.

This structure reflects real-world production practices and ensures a clear
separation of concerns between the client and server.

This root repository exists to provide documentation, architectural context,
and links to all related codebases.
