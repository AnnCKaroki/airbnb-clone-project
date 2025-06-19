# airbnb-clone-project

## Project Description
This is a full-stack clone of AirBnB booking platform. The web app allows users to browse property listings, view detailed property information, and complete bookings. 

### Tech Stack
Frontend: HTML,CSS and Javascript(React)  

Version control: Git and Github  

Design: Figma  

## 🧠 UI/UX Design Planning

### 🎯 Design Goals
- Make booking easy and fast
- Keep design consistent across pages
- Ensure pages load quickly
- Make it work well on phones and tablets

### ✨ Key Features
- Property search and filters
- View full details of a property
- Checkout and payment process
- User login and signup

### 🗂️ Primary Pages Overview

| Page | Description |
|------|-------------|
| **Property Listing View** | Shows many properties in a grid with search and filters |
| **Listing Detailed View** | Shows full info about one property, including photos and booking options |
| **Simple Checkout View** | Lets users confirm booking and make a payment |

### 💡 Why User-Friendly Design Matters

A clean and easy-to-use design helps people:
- Find properties faster
- Trust the system more
- Complete bookings without confusion

## 🎨 Figma Design Specifications

### 🎨 Color Styles
- **Primary Color:** `#FF5A5F`
- **Secondary Color:** `#008489`
- **Background:** `#FFFFFF`
- **Main Text:** `#222222`
- **Subtext:** `#717171`

### ✍️ Typography
- **Main Font:** Circular
  - Font weight: Medium (500)
  - Font size: 16px
- **Headings:** Circular Bold (700), sizes 24px–32px
- **Body Text:** Circular Book (400), 14px

### 🧠 Why Design Specs Matter

Knowing the exact fonts and colors in the design:
- Helps match the mockup
- Makes the UI consistent
- Speeds up development

## 👥 Project Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| **Project Manager** | Keeps track of timelines, coordinates team work |
| **Frontend Developers** | Build the UI, make it responsive |
| **Backend Developers** | Create APIs, connect to the database |
| **Designers** | Make mockups, plan user experience |
| **QA/Testers** | Test the site, find and report bugs |
| **DevOps Engineers** | Handle deployment, server setup, CI/CD |
| **Product Owner** | Defines project needs, manages features |
| **Scrum Master** | Leads team meetings, removes blockers |

## 🧩 UI Component Patterns

These are the main reusable components we'll build:

### 🔝 Navbar
- Logo
- Search bar
- User links
- Works on all screen sizes

### 🏠 Property Card
- Property image
- Title, price, location
- Favorite button
- Responsive layout

### 🔻 Footer
- Site links (About, Contact)
- Social media icons
- Copyright



**BELOW ARE ANSWERS FOR THE PRODEV BACKEND TASK**



## Project Description

This is a clone of the Airbnb platform built to learn and practice full-stack development using modern tools and workflows.

**Tech Stack:**
- Django (Backend)
- PostgreSQL/MySQL (Database)
- GraphQL (API Queries)
- Docker
- GitHub Actions


## Team Roles

| Role              | Responsibility |
|-------------------|----------------|
| Project Manager   | Coordinates the project and team |
| Frontend Developer| Builds the user interface |
| Backend Developer | Creates server logic and APIs |
| Designer          | Designs UI/UX mockups |
| QA / Tester       | Tests features and reports bugs |
| DevOps Engineer   | Handles deployment and CI/CD |
| Product Owner     | Defines features and priorities |
| Scrum Master      | Facilitates agile processes |


## Technology Stack

| Technology   | Purpose |
|--------------|---------|
| Django       | Web framework for backend and APIs |
| PostgreSQL/MySQL | Stores all application data |
| GraphQL      | API tool to request only needed data |
| Docker       | Creates reusable app environments |
| GitHub Actions | Automates testing and deployment |


## Database Design

| Entity     | Sample Fields |
|------------|---------------|
| Users      | id, name, email, password |
| Properties | id, title, location, price, host_id |
| Bookings   | id, user_id, property_id, check_in, check_out |
| Reviews    | id, user_id, property_id, rating, comment |
| Payments   | id, booking_id, amount, status |

**Relationships:**
- A user can have many bookings.
- A booking belongs to one property.
- A property can have many reviews.
- A payment is linked to a booking.


## Feature Breakdown

| Feature            | Description |
|--------------------|-------------|
| User Management    | Register, log in, and manage profiles |
| Property Listings  | Browse and search available properties |
| Booking System     | Book properties for specific dates |
| Review System      | Add and read property reviews |
| Payment Gateway    | Secure booking payments |


## API Security

| Security Feature   | Purpose |
|--------------------|---------|
| Authentication     | Verifies user identity |
| Authorization      | Controls what users can access |
| Rate Limiting      | Prevents system overloads |
| Input Validation   | Protects against bad or malicious data |

Security helps protect user data, ensure safe payments, and prevent abuse.


## CI/CD Pipeline

**CI/CD** (Continuous Integration and Deployment) helps automate testing and deployment when code changes.

**Tools:**
- GitHub Actions – Automate tests and deployment steps
- Docker – Consistent app environments

CI/CD improves speed, reliability, and collaboration in development.





