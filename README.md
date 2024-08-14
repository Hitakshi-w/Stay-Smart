# StaySmart Web Application

This is a web application for booking and managing hotels. The application allows users to register, log in, view their profile, manage their bookings, and list their places for rent.

## Features

- User Registration and Login
- Profile Management
- Booking Management
- Place Listing and Management
- Responsive Design

## Technologies Used

- React
- React Router
- Axios
- Context API

### Prerequisites
- Node.js
- npm or yarn
  
**Project Structure**
- components/: Reusable components
- pages/: Page components for different routes
- context/: Context API for managing global state
- App.jsx: Main application component
- index.js: Entry point of the application

**Routing**
The application uses react-router-dom for client-side routing. Below are the main routes:

/: Home page
/login: Login page
/register: Registration page
/account: User profile page
/account/places: User's places page
/account/places/new: Form to add a new place
/account/places/:id: Form to edit an existing place
/place/:id: View a specific place
/account/bookings: User's bookings page
/account/bookings/:id: View a specific booking

**API Configuration**
The application uses Axios for making HTTP requests. The base URL for the API is set in App.jsx:
