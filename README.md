
# Brain Buzz - Online Examination System

**Brain Buzz** is an online examination system developed using PHP for the backend and CSS for styling. The platform consists of two user types: Students and Teachers. Students can attend quizzes, while Teachers can create and upload quizzes for students to participate in. Both user types can view their scorecards and the leaderboard for respective quizzes.

## Features

### 1. **Student Features:**
   - **Attend Quizzes**: Students can select and participate in quizzes created by the teacher.
   - **View Scorecard**: After completing the quiz, students can view their score and performance.
   - **View Leaderboard**: Students can check their rank and score among others who have taken the same quiz.

### 2. **Teacher Features:**
   - **Create Quizzes**: Teachers can create quizzes by defining questions, answers, and setting time limits.
   - **Upload Quizzes**: Teachers can upload quizzes for students to take.
   - **View Scorecards**: Teachers can view the scorecard of each student who has taken their quiz.
   - **View Leaderboard**: Teachers can check the leaderboard of each quiz, displaying the top-performing students.

## Installation

To set up the **Brain Buzz** system locally, follow these steps:

### Prerequisites:
- Web server like **Apache** or **Nginx**
- PHP 7.0 or higher
- MySQL or any other database for storing quiz data and results

### Steps:

1. **Clone the repository** (or download the files).
   ```bash
   git clone <repository-url>
   ```
   
2. **Setup the database**:
   - Create a new database in MySQL.
   - Import the provided SQL schema  to set up tables for quizzes, students, teachers, and results.

3. **Configure PHP**:
   - Make sure you have PHP installed and configured with your web server.
   - Configure database connection settings in `config.php` (e.g., set database credentials).
   
4. **Upload the files**:
   - Place the PHP files and the CSS files on your web server.
   
5. **Access the system**:
   - Open your browser and navigate to `http://localhost/brain_buzz/` to use the system.
   
6. **Login**:
   - Teachers can register and log in to create and upload quizzes.
   - Students can register and log in to take quizzes and view their scorecard.



## Technologies Used

- **PHP**: Server-side scripting language for backend logic.
- **MySQL**: Database management system for storing quiz questions, answers, scores, and user data.
- **CSS**: For styling and creating a responsive user interface.

## Contribution

Feel free to fork the repository and submit pull requests. Contributions are always welcome!

### How to Contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Create a new pull request.

