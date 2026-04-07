# Web Calendar Client Side

A comprehensive web-based calendar application built with React, featuring user authentication and event management. This project provides a daily and weekly view of events, allowing users to create, update, and delete appointments seamlessly.

## 🚀 Features

- **User Authentication:** Secure Sign In and Sign Up pages with form validation.
- **Dynamic Views:** Switch between daily and weekly calendar views.
- **Event Management:**
  - Create new events with titles, descriptions, and time slots.
  - Edit existing events.
  - Delete unwanted events.
- **Interactive Calendar:** Mini-calendar picker for quick navigation to specific dates.
- **Responsive Design:** Built with Chakra UI for a modern and responsive user interface.
- **Real-time Updates:** Integration with React Query for efficient data fetching and caching.

## 🛠️ Technologies Used

### Frontend
- **React (Vite):** Core framework and build tool.
- **Chakra UI:** Component library for styling and layout.
- **Redux Toolkit:** State management for user authentication and date picking.
- **React Query:** Server state management and API data fetching.
- **React Hook Form & Yup:** Form handling and schema-based validation.
- **Moment.js:** Date and time manipulation.
- **Framer Motion:** Smooth animations and transitions.


## 📂 Project Structure

- `src/api`: API service functions using `fetch`.
- `src/components`: Reusable UI components (Button, Input, CalendarPicker, etc.).
- `src/helpers`: Utility functions for date calculations.
- `src/icons`: SVG icon components.
- `src/pages`: Main application pages (Home, SignIn, SignUp, PageNotFound).
- `src/reducers`: Redux slices for global state.
- `src/store`: Redux store configuration.
- `src/yup`: Validation schemas.

