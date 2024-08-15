# Welcome to my Portfolio
Hi, I am **Connor Jones**, an undergraduate at **Weber State Univeristy** majoring in **Computer Science**
## Projects
Below are a few of the projects I have worked on:
## [Banking Application](https://github.com/Cojo99/Portfolio-Site/tree/main/Banking-App)

> Click the link above to view the code in GitHub!

![Banking app gif demo](/gifs/banking-app.gif)

### Description
Banking Application Development: MERN Full-Stack Implementation

For this project, I built on a basic banking application into a fully functional, role-based system using React for the front end and a MongoDB/Node.js/Express back end. The application supports three user roles: Administrator, Employee, and Customer. Each of the roles has specific permissions and capabilities.

Frontend:

- **User Authentication**:
  - Implemented a login system requiring a username, password, and verification of credentials for added security.
- **Elevated Access**:
  - Administrators can elevate and demote user roles, changing users between Customer, Employee, and Administrator roles. Admins can access all other pages of the site.
- **Account Management**:
  - Customers can manage three types of accounts: savings, checking, and investment. Each account allows for depositing, withdrawing, and transferring funds. Employees can perform similar actions for any customer account as well as transfer money between customers.
- **Transaction History**:
  - Provided both comprehensive and individual transaction histories, displaying dates and transaction details.
- **Simple, User-friendly Design**:
  - Utilized Bootstrap for a clean and consistent UI, ensuring a professional look and feel with a user-friendly interface.

Backend:

- **Secure Authentication**:
  - Implemented password hashing using sha-256 to enhance security, storing only the hashed version of passwords in the database.
- **CRUD Operations**:
  - Supported all front-end functionalities, including account operations and user role management.
- **Role-Based Access Control**:
  - Ensured appropriate access levels for different user roles, with administrators having full access and employees and customers having restricted more restricted access.

### Summary: 
This project demonstrates my ability to design and implement a full-stack application with secure authentication, role-based access control, and a clean, user-friendly interface.

## [Hangman Game](https://github.com/Cojo99/Portfolio-Site/tree/main/hangman-game)

> Click the link above to view the code in GitHub!

![hangman gif demo game](/gifs/hangman-game.gif)

### Description
Hangman Game Development: Full-Stack Group Project

In this group project, we developed a full-stack Hangman game using React for the front end, Express for the backend, and MongoDB to store user information and high scores. We designed the game so it would be a fun experience for the user and feel like a real game with lots of possible words.

Game Logic:

- **User Experience**:
  - Upon opening the page, users are prompted to enter their name after which the game begins with a typical hangman setup. Players guess letters, with correct guesses revealing the letters and incorrect guesses progressing the hangman and displaying the wrong letters.
Session Management: User sessions were implemented to store the player's name throughout the game, avoiding the need to re-enter it after each round.
- **Random Word Selection**:
  - The game randomly selects words from a file containing over 1,000 possible words, ensuring a random, authentic game experience. The length of each word varies.
- **Fair Play**:
  - The chosen word is never sent to the client until the game ends, preventing players from cheating by inspecting the DOM.
  
High Scores:

- **High Schores**:
  - After each game, a top 10 high scores are displayed, showing the best scores for words of the same length. The high scores list tracks the player's name, the number of guesses made, and the length of the word.
Persistent Scoring: High scores are stored in a MongoDB database, allowing for persistent tracking of the top players.
Collaboration and Code Management:

- **Version Control**:
  - The project was managed using GitHub, with all group members contributing through commit, push, and pull operations, ensuring seamless collaboration and version control.

### Summary: 
This project highlights my ability to work in a team, efficiently utilize a version control system, and develop a complete, interactive web-based game that focuses on both functionality and user experience.
