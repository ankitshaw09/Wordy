# Language Learning Game - Django Application
# or
# Quiz Game From Django 
## Overview

This Django application is designed to help users improve their language proficiency through interactive exercises and activities. It includes a frontend UI, backend logic for scoring, and a database to store user progress and language data.

## Setup Instructions

1. Clone the repository to your local machine.
2. Create a virtual environment and activate it.

      ``` bash
      pip install virtualenv 
      
      virtualenv venv
      
      venv/Scripts/activate

3. Install the required dependencies using `pip install -r requirements.txt`.

5. Apply the migrations using `python manage.py migrate`.
    ```bash
    python manage.py migrate

6. Create a superuser using `python manage.py createsuperuser` to access the Django admin panel for content management.
      ```bash
      python manage.py createsuperuser
      <!-- and create username or password  -->
7. Start the development server using `python manage.py runserver`.
    ```bash 
    python manage.py runserver
    ```
8. you get a url ,
```
Copy this URL into your browser:  http://127.0.0.1:8000/
```

9.  for admin authentication  ```http://127.0.0.1:8000/admin```

## Requirements

### Frontend Development

- The frontend provides an interactive and user-friendly interface for the language learning quiz.
- Clear instructions and feedback are provided to users during the exercises.


- `Html`
- `CSS`
- `JavaScript`
- `Bootstrap`

### Backend Development

- Backend APIs handle the language learning logic and scoring system.
- An authentication system is implemented for user registration and login.
- Endpoints are created to fetch exercise questions and submit user answers for evaluation.
- `Python`
- `Django Framework`
- `Rest Framework`


### Database Management

- A database is set up to store user language proficiency levels, progress, and exercise data.
- The database schema is designed to efficiently manage user data.

### Language Selection

- Users can choose the language they want to learn from a list of available languages.
- Language-specific exercises are implemented based on the user's selection.

### Scoring and Progress Tracking

- A scoring system evaluates user performance in each exercise (0-5).
- Scoring is based on the difficulty of the question.
- User progress, including completed exercises and proficiency levels, is tracked and displayed.
- A leaderboard is created to display the top-performing users, fostering healthy competition and encouraging engagement. Leaderboard is based on the language.


## Setup Instructions

1. Clone the repository to your local machine.
2. Create a virtual environment and activate it.
3. Install the required dependencies using `pip install -r requirements.txt`.
4. Create a new PostgreSQL database and update the database settings in `settings.py`.
5. Apply the migrations using `python manage.py migrate`.
6. Create a superuser using `python manage.py createsuperuser` to access the Django admin panel for content management.
7. Start the development server using `python manage.py runserver`.

## How to Play

1. Visit the application in your web browser.
2. Register or log in to your account.
3. Choose the language you want to learn.
4. Start the quiz and answer the questions based on your proficiency level.
5. Your progress and scores will be tracked in your profile.

## Code Organization

- `backend/`: Contains backend logic and APIs.
- `frontend/`: Includes frontend UI components.
- `templates/`: Stores HTML templates for rendering pages.
- `static/`: Contains static files (CSS, JavaScript, images).
- `media/`: Used for storing user-uploaded content.
- `db/`: Database setup and migrations.
- `config/`: Application configuration settings.

## Comments

- The code is well-organized and follows best practices for both frontend and backend development.
- Detailed comments have been provided to explain the purpose and functionality of each code section.

## Resources

- [UsingEnglish Quizzes](https://www.usingenglish.com/quizzes/29.html)

## Contributors

- [Ankit shaw ](https://github.com/ankitsw09)



Feel free to reach out if you have any questions or need further assistance! Happy coding!