## InternSync - Internship Tracker System

A lightweight, client-side web app for tracking internship applications, rating companies, and visualising your results. No backend or database required. Everything runs in the browser.

## Features

- Login — Password to protect access to the system
- Add Applications — Log a internship place and choose its status (Accepted / Pending / Rejected)
- Stats Cards — Live counts for Total, Accepted, Pending, and Rejected applications
- Charts — Doughnut chart for rating distribution and bar chart per company rating, on the dashboard
- List View — Display all the internship place list with searchable, filterable table with edit and delete actions
- Star Ratings — Rate each accepted internship place from 1 to 5 stars
- Leaderboard — Internship place ranked by rating with medals and a horizontal bar chart
- Dark Mode — Toggle persisted across all pages

## How to Access

- Open the live link
- On the login page, enter the credentials below
- Click Login
- Email: aliyah@gmail.com | Password: 12345

## Pages

- `index.php` - Login 
- `dashboard.php` - Stats overview and charts 
- `total.php` - Full application list 
- `rating.php` - Star rating for accepted companies
- `top.php` - Leaderboard 

## Project Structure

- index.php - Login
- dashboard.php - Dashboard
- total.php - Application list
- rating.php - Star rating
- top.php - Leaderboard
- css/
  - style.css - Login styles
  - style1.css - Dashboard styles
  - style2.css - Rating page styles
  - style3.css - Top page styles
  - style4.css - List page styles
- img/
  - logo.png - System logo

## Libraries Used

- Bootstrap 5.3.8 - Layout, components, dark mode 
- Bootstrap Icons 1.13.1 - Icons 
- Chart.js - Dashboard and leaderboard charts
- tsParticles 2 - Animated background on login page 
- Google Fonts - Saira Condensed, Typography 

## Data Storage

- Data is stored in `localStorage` - no server required.
- Clearing browser storage will reset all data.

© 2026 InternSync | Aliyah
