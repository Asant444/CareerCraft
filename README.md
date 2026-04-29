# CareerCraft – CV Builder & Interview Prep Platform

## Overview

CareerCraft is a modern web-based career preparation platform designed to help users create professional CVs and prepare for job interviews using an AI-powered interview coach.

The platform combines professional CV creation with interview preparation tools in one complete system.

This project is built using pure HTML, CSS, and JavaScript with a clean responsive UI and interactive user experience.

---

## Features

### 1. Home Page

A professional landing page introducing the platform with:

* Hero section
* Feature cards
* Quick navigation
* Call-to-action buttons

---

### 2. CV Templates

Users can choose from multiple professional templates:

* Classic
* Modern Dark
* Corporate Blue
* Natural Green
* Minimal
* Executive

Each template provides a different design style for different industries and career levels.

---

### 3. CV Builder

Users can create a professional CV by filling:

* Personal Information
* Professional Summary
* Work Experience
* Education
* Skills
* Languages

Additional features include:

* Live CV Preview
* Copy CV as text
* Template switching
* PDF download simulation

---

### 4. AI Interview Coach

An interactive chatbot helps users prepare for interviews for roles such as:

* Software Engineer
* Product Manager
* UX Designer
* Data Analyst
* Marketing Manager
* Financial Analyst
* HR Manager
* Custom Job Roles

Features include:

* Role-specific interview preparation
* Common interview question practice
* Salary negotiation tips
* STAR method guidance
* Behavioral and technical interview coaching

---

## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript (Vanilla JS)

### UI Design

* Google Fonts
* Responsive Design
* Custom CSS Variables
* Modern Card-Based Layout

### AI Integration

* Anthropic Claude API (Interview Coach)

---

## Project Structure

```text
CareerCraft/
│
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/ (optional)
```

---

## How to Run the Project

### Method 1: Direct Browser Open

Simply open:

```text
index.html
```

in any browser.

---

### Method 2: VS Code Live Server (Recommended)

1. Open project folder in VS Code
2. Install Live Server extension
3. Right click `index.html`
4. Click **Open with Live Server**

This provides automatic reload during development.

---

## Current Limitations

The current version of CareerCraft is a strong frontend prototype, but it still has some limitations that future contributors can improve.

### What the Project Currently Lacks

* No real backend system
* No database for saving user CVs
* No user authentication (Login / Signup)
* PDF download is currently simulated only
* No DOCX export support
* API key exposure due to direct frontend API calls
* No ATS (Applicant Tracking System) resume checker
* No admin dashboard
* No cloud storage for resumes
* No multi-language support
* No dark/light mode toggle
* No profile image upload feature
* No resume analytics or job matching system

---

## Contribution Opportunities

Other developers can improve this project by adding advanced real-world features.

### Suggested Features for Contributors

### Backend Development

* Node.js + Express backend
* PHP backend
* Python Flask / Django backend
* Secure API handling
* Authentication system
* Session management

### Database Integration

* MySQL
* PostgreSQL
* MongoDB
* User profile storage
* Resume history tracking

### CV System Improvements

* Real PDF generation
* DOCX export
* Drag-and-drop section editing
* Profile photo upload
* Resume version history
* Auto-save functionality

### AI Features

* AI-generated CV improvement suggestions
* ATS compatibility score checker
* Keyword optimization for job descriptions
* Smart job matching recommendations
* Cover letter generator

### UI/UX Improvements

* Dark mode / Light mode toggle
* Mobile-first optimization
* Better animations and transitions
* Dashboard for saved resumes
* Improved chatbot interface

### Advanced Interview System

* Voice interview simulation
* Video mock interview system
* Interview score tracking
* Personalized feedback reports
* Company-specific interview preparation

These additions can help transform CareerCraft from a frontend project into a full production-ready platform.

---

## Important Note About API

The Interview Coach currently uses a direct frontend API request.

### Recommended Improvement

Move the API request to a backend server such as:

* Node.js + Express
* PHP Backend
* Python Flask / Django

This protects:

* API Keys
* Request Security
* Usage Limits
* Authentication

Direct frontend API exposure is not secure for production use.

---

## Future Improvements

Possible upgrades include:

* Real PDF generation
* User authentication
* Save CV to database
* Export to DOCX
* LinkedIn profile import
* ATS score checker
* AI-powered CV improvement suggestions
* Dark/Light mode toggle
* Admin dashboard

---

## Learning Outcomes

This project demonstrates:

* Frontend UI/UX design
* DOM manipulation
* State management in JavaScript
* Responsive web design
* API integration
* Real-world project architecture
* Professional GitHub project presentation

---

## Author

Developed as a portfolio project to demonstrate:

* Frontend Development Skills
* UI/UX Design
* JavaScript Problem Solving
* Real-World Project Structuring

---

## License

This project is for educational and portfolio purposes.

You may customize and extend it for personal learning and professional portfolio presentation.
