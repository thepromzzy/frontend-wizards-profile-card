Frontend Wizards Stage 0: Profile Card
This project is a responsive, accessible Profile Card built with semantic HTML, CSS (Flexbox and Grid), and vanilla JavaScript. It meets all core requirements for the Frontend Wizards internship Stage 0, including data-testid attributes for automated testing, semantic markup, responsiveness across devices, and interactivity (avatar file upload and real-time clock). The design is modern and polished, inspired by contemporary profile card layouts, ensuring an excellent user experience.
Features

Semantic HTML: Uses <article>, <figure>, <nav>, <section>, and headings for structure and accessibility.
Responsive Layout: Stacks vertically on mobile; avatar on the left and content on the right for tablet/desktop.
Avatar Upload: Clicking/tapping the avatar directly opens the file explorer to upload an image, displayed via URL.createObjectURL.
Real-Time Clock: Displays current time in milliseconds, updating every second using Date.now() and setInterval.
Social Links: Inline SVG icons for Twitter (X), LinkedIn, and GitHub, opening in new tabs with rel="noopener noreferrer".
Keyboard Navigation: Avatar and links are focusable with visible focus styles (Tab, Enter, Space keys).
Accessible Elements: Includes alt text for images and ARIA considerations where needed.
Polished Design: Uses Google Fonts ('Aleo'), subtle animations, and a clean layout with no emojis in section headers.

Project Structure

index.html: Core structure with semantic HTML and embedded SVG social icons.
style.css: Styles for responsiveness, layout, and modern design (Flexbox, Grid, media queries).
script.js: Handles avatar upload, real-time clock, and keyboard accessibility.
README.md: This documentation file.

Prerequisites

A modern web browser (e.g., Chrome, Firefox, Edge).
Git installed for cloning (optional for local testing; browser can open index.html directly).
No dependencies or build tools required.

How to Clone and Run Locally

Clone the Repository:
Ensure Git is installed (git --version in terminal/command prompt).
Run the following command in your terminal or command prompt:git clone https://github.com/thepromzzy/frontend-wizards-profile-card.git

Replace your-username with your GitHub username.
Navigate to the project folder:cd frontend-wizards-profile-card

Open the Project:
Double-click index.html to open in a browser, or use a local server (e.g., VS Code Live Server).
Alternatively, run:open index.html # macOS
start index.html # Windows

Interact with the Card:
Click/tap the avatar to upload an image (opens file explorer).
Verify the time updates every second.
Test social links (open in new tabs) and keyboard navigation (Tab, Enter, Space).

Step-by-Step Development Process
The following steps outline how the project was built to meet the task requirements, ensuring supervisors can verify compliance and implementation details.

Initialize Project:

Created a GitHub repository named frontend-wizards-profile-card.
Set up files: index.html, style.css, script.js, README.md.
Initialized Git: git init, added files, committed, and pushed to remote.

Build Semantic HTML:

Used <article data-testid="test-profile-card"> as the root container.
Added avatar in <figure> with <img data-testid="test-user-avatar"> and hidden <input type="file">.
Included name in <header> with <h2 data-testid="test-user-name">.
Added bio in <p data-testid="test-user-bio">.
Displayed time in <div data-testid="test-user-time"> within a styled section.
Added social links in <nav data-testid="test-user-social-links"> with <ul> and <a> tags (e.g., data-testid="test-user-social-twitter").
Created hobbies and dislikes in <section> tags with data-testid="test-user-hobbies" and data-testid="test-user-dislikes", using <ul> and <li>.

Style with CSS:

Used Flexbox for header (avatar and name) and Grid for hobbies/dislikes.
Applied media queries for responsiveness:
Mobile (<768px): Vertical stack, smaller avatar (80px-100px).
Tablet/Desktop (≥768px): Avatar left, content right.

Styled social links as circular buttons with SVG icons, hover effects, and focus outlines.
Ensured layout handles variable content lengths (word-wrap, max-width).

Add JavaScript Interactivity:

On DOM load:
Set real-time clock with setInterval to update Date.now() every second.
On avatar click, trigger file input to open file explorer.
On file change, update img src with URL.createObjectURL and set alt text.
Added keyboard event listener for avatar (Enter/Space triggers click).

Used vanilla JavaScript, no external libraries.

Ensure Accessibility and Testability:

Added descriptive alt text for avatar and social icons.
Ensured focusable elements (avatar, links) with visible :focus styles.
Verified all data-testid attributes match requirements exactly for automated tests.
Tested keyboard navigation (Tab through elements, Enter/Space on avatar).

Validate and Test:

Tested locally in browser dev tools (Chrome, Firefox) for responsiveness and errors.
Verified image upload, time updates, and link functionality.
Ensured no console errors and layout stability with long content.

Deploy and Document:

Deployed to GitHub Pages (Settings > Pages > Source: main, root) or Netlify (drag-and-drop folder).
Updated README with live URL and cloning instructions.
Pushed final changes to GitHub.

Testing Notes

Automated Testing: All elements are discoverable via data-testid attributes (e.g., test-profile-card, test-user-time).
Time Accuracy: Updates every second, within reasonable delta of Date.now().
Avatar Upload: Clicking/tapping opens file explorer; uploaded images display correctly.
Accessibility: Alt text, keyboard focus, and semantic markup ensure WCAG compliance.
No Dependencies: Runs in any modern browser without setup.

GitHub Pages:
Go to repo Settings > Pages.
Set Source to main branch, root folder.
Save and wait for deployment (URL provided in Settings).
