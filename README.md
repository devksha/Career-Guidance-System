# Career Guidance System

Career Guidance System is a comprehensive web-based platform aimed at empowering students, job seekers, and professionals to make informed career decisions. The system offers a rich, interactive experience by combining personalized career recommendations based on individual profiles with an AI-powered chatbot to answer career-related questions instantly.

- **Personalized Career Guidance:** Tailored career suggestions based on user inputs.
- **Interactive Chatbot:** Instant answers and career advice via chatbot interface.
- **Database Integration:** Uses SQLite (`careerguide.db`) to store career info and user data.
- **Responsive and Modern UI:** Clean design using SCSS and CSS.
- **Multi-page Application:** Includes homepage, personalized guidance, chatbot, and database creation scripts.


## Project Structure

Career-Guidance-System/
│
├── assets/
│ └── hero.png # Hero image used on UI
│
├── css/
│ ├── chatbot.css # Styles for chatbot
│ └── main.css # Main stylesheet
│
├── scss/
│ ├── _careers.scss
│ ├── _configure.scss
│ ├── _footer.scss
│ ├── _header.scss
│ ├── _hero.scss
│ ├── _personalized.scss
│ ├── _variables.scss
│ ├── main.css # Compiled CSS from SCSS
│ └── main.css.map # Source map for CSS
│
├── chatbot.js # Front-end chatbot logic (JavaScript)
├── chatbot.php # Back-end chatbot logic (PHP)
├── create_database.php # Script to create & initialize SQLite DB
├── careerguide.db # SQLite database file
├── index.html # Main landing page
├── main.js # Main JavaScript file
├── personalized.html # Personalized guidance page (HTML)
└── personalized.php # Personalized guidance page (PHP)


## Technologies Used

- **Frontend:** HTML5, CSS3, SCSS, JavaScript
- **Backend:** PHP
- **Database:** SQLite (`careerguide.db`)
- **Version Control:** Git

---

## Installation & Setup

1. Clone the repository:
   git clone https://github.com/devksha/Career-Guidance-System.git
   cd Career-Guidance-System
   
Set up the environment:

Install a local server environment like XAMPP or WAMP.
Make sure PHP and SQLite extensions are enabled.
Place the project folder inside your web server’s root directory:
For XAMPP, typically C:\xampp\htdocs\
For WAMP, typically C:\wamp\www\

Create the database:

Run the script create_database.php by navigating to it in your browser


Usage
Use the home page to start exploring career options.

Navigate to Personalized Guidance for tailored career recommendations.

Chat with the interactive chatbot for instant career-related assistance.

All data is stored locally in the SQLite database.

Contribution
Contributions are welcome! If you want to contribute:

Fork the repo.

Create a new branch (git checkout -b feature-name).
Make your changes.
Commit your changes (git commit -m "Add some feature").
Push to your branch (git push origin feature-name).
Open a Pull Request.

Contact
If you have any questions or want to collaborate, feel free to reach out:
Name: Deeksha S
Email: deekshas.corp@gmail.com
GitHub: https://github.com/devksha

Acknowledgments
Thanks to all open source projects and libraries used.

Inspired by the need to help students and job seekers with better career choices.
