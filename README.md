Frontend Wizards Profile Card
Overview
The Frontend Wizards Profile Card is a responsive and accessible web-based profile card designed to showcase a developer's personal information, including their avatar, bio, social media links, hobbies, dislikes, and current time. Built with HTML, CSS, and JavaScript, this project emphasizes clean design, user interaction, and accessibility. It features a modern layout with a focus on responsiveness across various devices and includes high-contrast mode support for accessibility.
Features

Profile Information: Displays the user's name, title, and bio.
Avatar Upload: Allows users to upload a custom profile image by clicking the avatar or using keyboard navigation (Enter/Space).
Dynamic Time Display: Updates the current time every second using JavaScript.
Social Media Links: Links to Twitter/X, LinkedIn, and GitHub with accessible SVG icons.
Hobbies and Dislikes: Lists user hobbies and dislikes in a clean, styled format.
Responsive Design: Adapts to various screen sizes (desktop, tablet, mobile) with media queries.
Accessibility: Supports keyboard navigation and high-contrast mode for better accessibility.
Custom Styling: Uses the Aleo font from Google Fonts and a consistent color scheme with hover effects.

Technologies Used

HTML5: For semantic structure.
CSS3: For styling, including Flexbox, Grid, and media queries for responsiveness.
JavaScript: For dynamic time updates and avatar upload functionality.
Google Fonts: For the Aleo font used in headings.
SVG Icons: For social media links.

Prerequisites
To run this project locally, ensure you have the following:

A modern web browser (e.g., Chrome, Firefox, Edge).
A code editor (e.g., VS Code).
Git installed to clone the repository.
A local server (e.g., Live Server extension in VS Code or Node.js http-server) to serve the files.

Installation and Setup
Follow these steps to run the project locally:

Clone the Repository:
git clone https://github.com/thepromzzy/frontend-wizards-profile-card.git

Navigate to the Project Directory:
cd frontend-wizards-profile-card

Open the Project:

If you have a local server like Live Server in VS Code, right-click index.html and select "Open with Live Server."
Alternatively, use a Node.js-based server:npm install -g http-server
http-server

Then, open your browser and navigate to http://localhost:8080.

View the Profile Card:Open the provided URL (e.g., http://localhost:8080) in your browser to see the profile card in action.

Project Structure
frontend-wizards-profile-card/
├── index.html # Main HTML file for the profile card
├── style.css # CSS file for styling the profile card
├── script.js # JavaScript file for dynamic functionality
├── images/ # Directory for storing avatar images (e.g., promise 1.jpg)
└── README.md # Project documentation

Usage

View Profile: Open index.html in a browser to see the profile card with the default avatar, bio, social links, hobbies, and dislikes.
Update Avatar: Click the avatar image or press Enter/Space when focused to upload a new profile picture (supports image formats like PNG, JPG).
Check Time: The current time updates automatically every second in the "Current Time" section.
Social Links: Click the social media icons to visit the respective profiles (Twitter/X, LinkedIn, GitHub).
Responsive Testing: Resize the browser window or use developer tools to test the responsive layout on different screen sizes.

Accessibility Features

Keyboard Navigation: The avatar image is focusable and can be interacted with using the Enter or Space key.
High-Contrast Mode: Enhanced borders and contrast for users with visual impairments.
Semantic HTML: Uses proper HTML5 elements like <article>, <header>, <nav>, and <section> for better screen reader support.
Alt Text: Avatar image includes descriptive alt text for accessibility.

Known Limitations

The avatar image (promise 1.jpg) must be present in the images/ directory for the default avatar to display correctly. If not available, update the src attribute in index.html or upload a new image.
The time display currently shows a raw timestamp (Date.now()). For a formatted time, modify the updateTime function in script.js (see Future Improvements).

Future Improvements

Format the time display to show a human-readable format (e.g., HH:MM:SS).
Add form validation for avatar uploads (e.g., file size or type restrictions).
Implement a dark mode toggle for better user customization.
Add animations for smoother transitions when changing avatars or hovering over links.
Include unit tests for JavaScript functionality using a testing framework like Jest.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a pull request.

Please ensure your code follows the existing style and includes appropriate comments.

Contact
For questions or feedback, reach out via:

GitHub: thepromzzy
LinkedIn: promiseayodeji
Twitter/X: @thepromzzy
