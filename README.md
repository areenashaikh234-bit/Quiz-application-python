# Quiz-application-python
questions ={
    "what is the capital of India?": "Delhi",
    "Which language is used for python development?": "Python",
    "How many days are there in a week?": "7"
    }
score=0
for question, answer in questions.items():
    user_answer = input(question+"")

    if user_answer.lower() == answer.lower():
        print("correct")
        score += 1
    else:
        print("wrong!")

print("\nQuiz completed!")
print("your score:", score, "/", len(questions))

