📝 Python Quiz Game

A simple and interactive Python Quiz Game where users answer multiple-choice questions and get scored based on their answers.
This project is perfect for learning Python basics like loops, conditionals, and lists.

🚀 Features

Multiple-choice quiz questions

Immediate feedback for correct/incorrect answers

Tracks and displays the user’s score

Console-based and beginner-friendly

Easy to add more questions

🛠️ Technologies Used

Python 3

📌 How It Works

The program displays a series of questions with multiple options.

The user inputs the option they think is correct.

The program checks the answer and updates the score.

After all questions are answered, the final score is displayed.

Simple and interactive console experience.

📂 Sample Code
print("Welcome to the Python Quiz Game!")

score = 0

questions = [
    {
        "question": "What is the capital of India?",
        "options": ["1. Mumbai", "2. Delhi", "3. Kolkata", "4. Chennai"],
        "answer": 2
    },
    {
        "question": "Which language is used for web development?",
        "options": ["1. Python", "2. JavaScript", "3. C++", "4. Java"],
        "answer": 2
    },
    {
        "question": "2 + 2 equals?",
        "options": ["1. 3", "2. 4", "3. 5", "4. 22"],
        "answer": 2
    }
]

for q in questions:
    print("\n" + q["question"])
    for option in q["options"]:
        print(option)
    user_answer = int(input("Enter the correct option number: "))
    
    if user_answer == q["answer"]:
        print("Correct!")
        score += 1
    else:
        print("Incorrect!")

print(f"\nQuiz Over! Your final score is: {score}/{len(questions)}")

📸 Example Output
Welcome to the Python Quiz Game!

What is the capital of India?
1. Mumbai
2. Delhi
3. Kolkata
4. Chennai
Enter the correct option number: 2
Correct!

Which language is used for web development?
1. Python
2. JavaScript
3. C++
4. Java
Enter the correct option number: 2
Correct!

2 + 2 equals?
1. 3
2. 4
3. 5
4. 22
Enter the correct option number: 2
Correct!

Quiz Over! Your final score is: 3/3

🎯 Learning Outcomes

Handling user input with input()

Using lists and dictionaries for question storage

Conditional statements (if-else)

Looping through multiple questions (for loop)

Creating a simple interactive console application

📁 Project Purpose

Beginner-friendly Python project

Good for college assignments and GitHub portfolios

Demonstrates Python fundamentals in a fun way

Can be extended to include more questions or a GUI interface
