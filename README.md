# Welcome to my Portfolio
Hi, I am **Connor Jones**! I recently graduated from **Weber State University** with my bachelor's degree in **Computer Science**. Since graduating, I have been able to work as a software developer creating websites used by over 1000 people by working with different teams to create user-friendly and functional UIs.
## Projects
Below are a few of the projects I have worked on:
## Central Hub for healthcare company##
### Description
Central Hub for Healthcare company: C# Razor Pages Full-Stack Implementation

In my current position, I have built a web application to help with different workflows throughout the clinic including scheduling, file maintenance, and policy management.

Frontend: 
- ** User Authentication**:
  - Integrated with active directory to use user's Windows Login to assign permissions to view certain content and pages, ensuring privacy and least-privilege policies.
- ** File Maintenance and data manipulation **
  - Created pages to allow user to add notes and be able to reorder the notes, giving them options to select different colors and categories. Created another page to allow users to upload PDFs and assign categories and add creation and effective dates. Departments were able to manage their own files, streamlining their processes.
 
Backend:
- **Data Management**:
  - Used MySQL database to maintain each department's data. Used 25+ tables to securely access sensitive information.
- **CRUD Operations**:
  - Built out funcionality that enabled users to input and export data including lists and PDFs, all wrapped up in a UI built around the user to ensure intuitive access.


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

In this group project, we developed a full-stack Hangman game using React for the front end, Express for the backend, and MongoDB to store user information and high scores. The game was designed to be easy to navigate and provide an enjoyable game-play.

Game Logic:

- **User Experience**:
  - Upon opening the page, users are prompted to enter their name after which the game begins with a typical hangman setup. Players guess letters, with correct guesses revealing the letters and incorrect guesses progressing the hangman and displaying the wrong letters.
Session Management: User sessions were implemented to store the player's name throughout the game, avoiding the need to re-enter it after each round.
- **Random Word Selection**:
  - The game randomly selects words from a file containing over 1,000 possible words, ensuring a random, authentic game experience. The length of each word varies.
- **Fair Play**:
  - The chosen word is never sent to the front end until the game ends. This prevents players from cheating by inspecting the DOM.
  
High Scores:

- **High Scores**:
  - After each game, the top 10 high scores are displayed, showing the best scores for words of the same length. The high scores list tracks the player's name, the number of guesses made, and the length of the word.
Persistent Scoring: High scores are stored in a MongoDB database, allowing for persistent tracking of the top players.
Collaboration and Code Management:

- **Version Control**:
  - The project was managed using GitHub, with all group members contributing through commit, push, and pull operations, ensuring seamless collaboration and version control.

### Summary: 
This project highlights my ability to work in a team, efficiently utilize a version control system, and develop a complete, interactive web-based game that focuses on both functionality and user experience.
