Frontend Wizards Profile Card
Overview
The Frontend Wizards Profile Card is a multi-page web application showcasing a developer's profile, contact form, and personal reflections. Built with HTML, CSS, and JavaScript, it emphasizes semantic HTML, accessibility, responsiveness, and a unified design. The project includes a home page with a profile card, a Contact Us page with form validation, and an About Me page with reflective sections.
Features

Home Page (Profile Card):
Displays the user's name, title, bio, avatar, social media links, hobbies, dislikes, and current time.
Allows avatar uploads via click or keyboard (Enter/Space).
Updates current time dynamically every second.

Contact Us Page:
Form with fields for full name, email, subject, and message.
Client-side validation: all fields required, valid email format, message ≥10 characters.
Displays error messages for invalid inputs and a success message on valid submission.
Fully accessible with labels, aria-describedby, and keyboard navigation.

About Me Page:
Reflective sections for bio, goals, areas of low confidence, note to future self, and extra thoughts.
Semantic structure with <main>, <section>, and <h2> elements.

Navigation:
Unified navigation bar across all pages for seamless transitions.

Design:
Consistent styling with Aleo font, red accents (#d63637), and card-based layouts.
Responsive across mobile, tablet, and desktop.
Supports high-contrast mode for accessibility.

Technologies Used

HTML5: Semantic structure.
CSS3: Flexbox, Grid, media queries for responsiveness.
JavaScript: Dynamic time updates, avatar upload, and form validation.
Google Fonts: Aleo font for headings.
SVG Icons: Social media links.

Prerequisites

Modern web browser (e.g., Chrome, Firefox, Edge).
Code editor (e.g., VS Code).
Git for cloning the repository.
Local server (e.g., VS Code Live Server or Node.js http-server).

Installation and Setup

Clone the Repository:git clone https://github.com/thepromzzy/frontend-wizards-profile-card.git

Navigate to the Project Directory:cd frontend-wizards-profile-card

Open the Project:
Use VS Code Live Server: Right-click index.html and select "Open with Live Server."
Or use Node.js http-server:npm install -g http-server
http-server

Then visit http://localhost:8080.

View the Application:
Home: http://localhost:8080/index.html
Contact: http://localhost:8080/contact.html
About: http://localhost:8080/about.html

Project Structure
frontend-wizards-profile-card/
├── index.html # Home page with profile card
├── contact.html # Contact Us page with form
├── about.html # About Me page with reflections
├── style.css # Shared CSS for all pages
├── script.js # JavaScript for home page
├── contact.js # JavaScript for contact form validation
├── images/ # Directory for avatar images (e.g., promise 1.jpg)
└── README.md # Project documentation

Usage

Home Page: View profile details, upload a new avatar, and check social links or time.
Contact Page: Fill out the form and submit. Validation ensures all fields are filled, email is valid, and message is ≥10 characters. Success message appears on valid submission.
About Page: Read reflective sections about the developer's bio, goals, and thoughts.
Navigation: Use the top navigation bar to switch between pages.
Responsive Testing: Resize the browser or use developer tools to test across devices.

Accessibility Features

Keyboard Navigation: Avatar and form inputs are keyboard-accessible (Enter/Space).
High-Contrast Mode: Enhanced borders for visibility.
Semantic HTML: Uses <nav>, <main>, <section>, <article>, etc.
Form Accessibility: Labels linked with for, error messages with aria-describedby.
Alt Text: Avatar image has descriptive alt text.

Known Limitations

Avatar image (promise 1.jpg) requires the images/ directory. Update src in index.html if unavailable.
Time display shows raw timestamp (Date.now()). Modify script.js for formatted time (e.g., HH:MM:SS).
Form submission is client-side only; no backend integration for sending messages.

Future Improvements

Format time display for readability.
Add backend integration for form submissions (e.g., email API).
Implement dark mode toggle.
Add animations for smoother transitions.
Include unit tests with Jest or React Testing Library.

Contributing

Fork the repository.
Create a branch: git checkout -b feature/your-feature.
Commit changes: git commit -m "Add your feature".
Push to branch: git push origin feature/your-feature.
Open a pull request.

License
MIT License. See LICENSE.
Contact

GitHub: thepromzzy
LinkedIn: promiseayodeji
Twitter/X: @thepromzzy

Submission

Live URL: [Deployed URL, e.g., Netlify/GitHub Pages]
GitHub Repo: https://github.com/thepromzzy/frontend-wizards-profile-card
