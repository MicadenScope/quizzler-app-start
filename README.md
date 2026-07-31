# 🧠 Quizzler App

A desktop quiz application built with Python and Tkinter.

The application presents True/False questions, keeps track of the user's score and provides immediate visual feedback after each answer.

The project demonstrates object-oriented programming, graphical user interfaces and working with quiz data.

## Features

- Interactive quiz interface
- True and False answer buttons
- Real-time score tracking
- Automatic progression through questions
- Visual feedback for correct and incorrect answers
- Object-oriented project structure
- Clean and simple user interface

## Technologies

- Python 3
- Tkinter
- Object-Oriented Programming (OOP)

The project only uses Python standard-library modules.

## Project Structure

```text
quizzler-app/
├── .gitignore
├── LICENSE
├── README.md
├── data.py
├── main.py
├── question_model.py
├── quiz_brain.py
└── ui.py
```

## File Overview

- `main.py` – starts the application
- `data.py` – contains the quiz questions
- `question_model.py` – defines the Question class
- `quiz_brain.py` – manages quiz logic and score
- `ui.py` – builds the graphical user interface

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

No additional packages need to be installed.

## Run the Application

Start the application:

```bash
python main.py
```

The quiz window will open.

## How It Works

1. Questions are loaded from the quiz data.
2. A `Question` object is created for every question.
3. The questions are stored in a question bank.
4. `QuizBrain` controls the quiz flow.
5. `QuizInterface` displays the graphical interface.
6. The score is updated after every answer.
7. The quiz ends after the final question.

## Concepts Demonstrated

This project demonstrates:

- Object-oriented programming
- Classes and objects
- Lists
- Loops
- Tkinter GUI development
- Event-driven programming
- Separation of logic and user interface
- Score tracking

## Dependencies

This project does not require a `requirements.txt` file because it only uses Python standard-library modules.

## Possible Improvements

- Load questions from an online API
- Multiple difficulty levels
- Timer for each question
- High-score system
- Multiple-choice questions
- Randomized question order
- Category selection
- Sound effects
- Dark mode
- Save previous quiz results

## Author

**Mick Kuyenda Misamu**  
MicadenScope

## License

This project is licensed under the MIT License.
