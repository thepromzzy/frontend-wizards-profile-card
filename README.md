Frontend Wizards – Stage 1
Multi-page profile app with a responsive profile card, contact form, and about page.
Live Demo: https://promiseprofilecard.netlify.app/ Repo: github.com/thepromzzy/frontend-wizards-profile-card

Features

Home Page: Profile card with avatar upload, bio, social links, hobbies, and live clock.
Contact Page: Fully validated form with real-time error messages and success feedback.
About Page: Reflective sections on goals, confidence, and future notes.
Responsive: Mobile, tablet, and desktop friendly.
Accessible: Keyboard navigation, ARIA labels, high-contrast support.
Testable: All required data-testid attributes included.

Tech Stack

HTML5
CSS3 (Flexbox, Grid, Media Queries)
Vanilla JavaScript
Google Fonts (Aleo)

Project Structure
/
├── index.html → Home (Profile Card)
├── contact.html → Contact Form
├── about.html → About Me
├── style.css → Shared styles
├── script.js → Home page logic
├── contact.js → Form validation
├── images/ → Avatar image
└── README.md

How to Run Locally

Clone the repo:
git clone https://github.com/thepromzzy/frontend-wizards-profile-card.git

Navigate to folder:
cd frontend-wizards-profile-card

Open in browser:

Use VS Code Live Server, or
Run: npx http-server → visit http://localhost:8080

Form Validation (Contact Page)

Field
Rule

Name
Required, min 2 chars, letters + spaces

Email
Valid format (user@domain.com)

Subject
Required

Message
Min 10 characters

Success message appears only after valid submission.

Accessibility

Semantic HTML (<main>, <nav>, <section>)
Labels linked with for
aria-describedby for error messages
Keyboard-navigable (Tab, Enter, Space)
High-contrast mode support

Submission Checklist

All data-testid attributes added

Form validation works

Success message shows only on valid submit

Responsive on all devices

Accessible & keyboard friendly

Clean, modular code

Built with passion by Promise JacobJunior Frontend Developer | Learning, Building, Growing
