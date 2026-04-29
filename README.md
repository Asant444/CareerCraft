## File Separation for CareerCraft

Your original project has the HTML, CSS, and JavaScript written inside one single file.

It should be separated into these 3 files:

---

# 1. index.html

Contains only:

* HTML structure
* Navigation
* Sections
* Forms
* Buttons
* Template cards
* CV Builder layout
* Interview Coach layout

At the top inside `<head>`:

```html
<link rel="stylesheet" href="style.css">
```

Before closing `</body>`:

```html
<script src="script.js"></script>
```

Also remove:

```html
<style>
...
</style>
```

and remove:

```html
<script>
...
</script>
```

from the original file.

---

# 2. style.css



This includes:

* Root variables
* Navigation styles
* Hero section
* Feature cards
* Template cards
* CV Builder styles
* CV Preview styles
* Chatbot styles
* Responsive design
* Media queries
* Buttons and forms

---

# 3. script.js

Move everything inside:

```html
<script>
...
</script>
```

into:

```javascript
script.js
```

This includes:

* showPage()
* selectTemplate()
* applyTemplate()
* updatePreview()
* Experience functions
* Education functions
* Skills functions
* Languages functions
* copyCV()
* Interview chatbot logic
* Claude API integration

---

# Final Folder Structure

```text
CareerCraft/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

# Important Note

Do not keep duplicate code.

After moving CSS and JavaScript:

* Remove internal `<style>` block
* Remove internal `<script>` block

Otherwise the project will become messy and harder to maintain.

---

# Professional GitHub Practice

This separation makes your project:

* Cleaner
* More professional
* Easier to debug
* Easier to maintain
* Better for deployment
* Better for collaboration

This is the standard structure used in real frontend projects.

---

# Current Limitations

The current version of CareerCraft is a strong frontend prototype, but it still has some limitations that future contributors can improve.

## What the Project Currently Lacks

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

# Contribution Opportunities

Other developers can improve this project by adding advanced real-world features.

## Suggested Features for Contributors

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
s