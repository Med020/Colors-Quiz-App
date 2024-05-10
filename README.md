# Colors-Quiz-App

This is a Quiz App built using Django, a high-level Python web framework. The application allows users to take quizzes, view their scores, and manage quizzes as administrators.

## Features

- **User Authentication**: Users can sign up, log in, and log out securely.
- **Quiz Taking**: Users can take quizzes with multiple-choice questions.
- **Scoring**: Scores are calculated automatically based on correct answers.
- **Admin Panel**: Administrators can manage quizzes, add new questions, and view quiz results.
- **Responsive Design**: The application is designed to work seamlessly on various devices.

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/your-username/quiz-app.git
    ```

2. Navigate to the project directory:

    ```
    cd quiz-app
    ```

3. Create a virtual environment:

    ```
    python -m venv venv
    ```

4. Activate the virtual environment:

    - On Windows:

        ```
        venv\Scripts\activate
        ```

    - On macOS and Linux:

        ```
        source venv/bin/activate
        ```

5. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

6. Apply database migrations:

    ```
    python manage.py migrate
    ```

7. Create a superuser (admin):

    ```
    python manage.py createsuperuser
    ```

8. Run the development server:

    ```
    python manage.py runserver
    ```

9. Access the application at `http://localhost:8000`.

## Usage

- **User Access**:
    - Navigate to `http://localhost:8000` in your web browser.
    - Sign up or log in with your credentials.
    - Take quizzes and view your scores.

- **Admin Access**:
    - Navigate to `http://localhost:8000/admin` in your web browser.
    - Log in with the superuser credentials.
    - Manage quizzes, add questions, and view quiz results.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Screenshots

Sign Up :
![Screenshot 2024-03-11 122819](https://github.com/Med020/Colors-Quiz-App/assets/125467087/3dbe9af1-0771-40f8-aaf7-573fcbb8d933)
Login :
![Screenshot 2024-02-26 131625](https://github.com/Med020/Colors-Quiz-App/assets/125467087/feb8277c-65a1-4b29-a238-a88fe54d9061)
Home :
![Screenshot 2024-05-09 171152](https://github.com/Med020/Colors-Quiz-App/assets/125467087/1d4e69c1-2fe3-462a-9762-f86a73697aa2)
Quiz :
![Screenshot 2024-05-09 171417](https://github.com/Med020/Colors-Quiz-App/assets/125467087/0bbeb414-ae84-4a87-9dd6-4364eaf58ec4)
Score :
![Screenshot 2024-05-09 171206](https://github.com/Med020/Colors-Quiz-App/assets/125467087/d90a3555-795e-4b86-93fb-e333920376bf)
Admin :
![Screenshot 2024-05-09 171226](https://github.com/Med020/Colors-Quiz-App/assets/125467087/eb004f28-8796-429b-9e3c-8023be85818d)

