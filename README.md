FT-WEB-101 - Task 1: Profile Page

A simple personal profile page built for the Field Training I (FT-WEB-101) course, Faculty of Computer Science & Engineering, New Mansoura University (Fall 2026-2027).

Name: Roqaya Walid El-Imam
Student ID: 225100992
What the page has
A header with my name as the main heading, and a navigation bar (name on the left, links on the right)
An image and a short "About me" section
Three cards in a row: Skills, Hobbies, and Goals
A contact form with Name and Email fields, each with a label
A button that switches the page between light and dark mode
A footer with a copyright line
How the dark mode works

Colours are stored as CSS variables on :root. When the button is clicked, JavaScript adds or removes the class dark on body. The dark colours are defined in CSS under body.dark, so JavaScript never sets colours directly.

Project structure
FT-WEB-101-Task1-225100992/
├── index.html      # The page content
├── css/
│   └── style.css   # Styling and the dark theme
├── js/
│   └── script.js   # The light/dark button
├── images/
│   └── me.jpg      # The image on the page
└── README.md
How to run
Download or clone this repository.
Keep the folder structure as shown above.
Open index.html in any web browser.

No installation or server is needed.

Built with
HTML
CSS (Flexbox, CSS variables)
JavaScript

No frameworks and no PHP.

Note on tools

I used an AI assistant (Claude) to help me build and understand this page. I am studying the code so I can explain it.
