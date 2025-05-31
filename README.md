# Spotify-Style-Auth-UI

A responsive, modern authentication UI styled like Spotify, built with HTML, CSS, and Bootstrap 5. This frontend-only implementation includes a Home page, Login page, and Registration page.

## Overview

This project replicates Spotify's visual style and user interface for authentication flows. It includes a Home page (index.html), Login page (login.html), and Registration page (register.html). The focus is purely on frontend design and layout - no backend functionality is included.

The application maintains the look and feel of Spotify's dark theme UI while providing a clean, intuitive user experience for authentication processes.

## Features

- **Responsive layout** using Bootstrap 5
- **Dark theme** matching Spotify's color scheme
- **Login page** with:
  - Email/Username and Password fields
  - Remember me option
  - Forgot password link
  - Social media login options
  - Link to registration
- **Registration page** with:
  - Username, Email, Password, and Confirm Password fields
  - Terms & Conditions acceptance
  - Social media registration options
  - Link back to login
- **Home page navigation** with account icon to access authentication pages
- **Modern, clean UI** with attention to Spotify's design patterns

## Tech Stack

- HTML5
- CSS3
- Bootstrap 5
- Bootstrap Icons for icon elements

## Project Structure

```
/project-root
├── index.html         # Home Page (unchanged)
├── login.html         # Login Page
├── register.html      # Registration Page
├── style.css          # Main stylesheet for Home Page
└── /assets
    └── css/
        └── auth.css   # Styles for Login and Registration pages
```

## How It Works

1. `index.html` serves as the main landing page (Home Page)
2. Users can navigate to the Login page by clicking the account icon in the navbar
3. From the Login page, users can:
   - Enter their credentials
   - Navigate to the Registration page
   - Return to the Home page
4. From the Registration page, users can:
   - Create a new account
   - Navigate back to the Login page
   - Return to the Home page

All transitions are through static links - no JavaScript logic or backend integration is implemented.

## Spotify-Inspired Design Elements

- **Color Scheme**:
  - Background: #191414 (Spotify Black)
  - Accent: #1DB954 (Spotify Green)
  - Text: #FFFFFF (White) and #B3B3B3 (Light Grey)
- **UI Components**:
  - Rounded buttons with uppercase text
  - Clean form fields with subtle borders
  - Social login options
  - "OR" divider between primary and secondary options

## Setup Instructions

1. Clone or download this repository
2. No build or installation steps required
3. Open `index.html` in any modern web browser

## Screenshots

*[Screenshots would be placed here showing each page]*

## Compatibility

- Compatible with all modern browsers
- Responsive design works on mobile, tablet, and desktop views

## Author

[OM PANDEY]

## Acknowledgments

- Inspired by Spotify's UI/UX design
- Built with Bootstrap 5
- Icons from Bootstrap Icons 
