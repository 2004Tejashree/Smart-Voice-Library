# Smart-Voice-Library
The Voice-Driven E-Library is an accessible web application designed to make digital reading available to everyone, including individuals with visual impairments or physical disabilities. By integrating advanced voice recognition and text-to-speech technologies, this project allows users to navigate, search, and interact with the library entirely through voice commands.

✨ Key Features
🗣️ Voice-Controlled Interface:
Complete hands-free navigation.
login and registration forms controllable via voice (e.g., "Set username...", "Submit").
Voice commands for searching books and navigating results.

♿ Accessibility First:
Text-to-Speech feedback for all interactions.
High-contrast UI with a toggleable Dark/Light Mode.
Aria-labels and semantic HTML for screen reader compatibility.

📱 Modern & Responsive Design:
3D interactive book visualization.
Responsive layout that works seamlessly across desktop and mobile devices.
Aesthetic UI with smooth transitions and glassmorphism elements.

📖 Library Management:
Browse featured books and categories.
Search functionality for finding specific titles.
"Read" mode for accessing book content.

🛠️ Technologies Used
Frontend: HTML5, CSS3, JavaScript (Vanilla)
Backend: PHP
Database: MySQL
APIs:
Web Speech API (SpeechRecognition & SpeechSynthesis)

🚀 Getting Started
1. Clone the repository:
git clone https://github.com/yourusername/voice-driven-e-library.git

2. Setup the Database:
Create a MySQL database.
Import the provided SQL schema (if available).
Update 
database.php
 with your database credentials.

3. Run the Application:
Host the files on a local server (e.g., using XAMPP, WAMP, or Apache).
Open 
index.html
 or 
welcome.php
 in a supported browser (Chrome/Edge recommended for Web Speech API support).

🎤 Voice Commands Guide
Login Page:
"Login" / "Register" - Switch modes.
"Username [name]" - Fills the username field.
"Password [key]" - Fills the password field.
"Submit" - Submits the form.
Dashboard:
"Search for [Book Name]" - Initiates a book search.
"Open book [number]" - Opens a specific book from results.
"Read book summary" - Reads the summary aloud.
