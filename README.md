# Quiz-Game_Staxtech_project
# Simple Python Quiz Game

score = 0

print("Welcome to the Python Quiz Game!")
print("Let's begin...\n")

# Question 1
print("1. Which data type is used to store text?")
print("a) int\nb) float\nc) string\nd) bool")
answer = input("Enter your answer: ")
if answer.lower() == "c":
    print("Correct!\n")
    score += 1
else:
    print("Wrong!\n")

# Question 2
print("2. Which keyword is used to define a function in Python?")
print("a) func\nb) def\nc) function\nd) define")
answer = input("Enter your answer: ")
if answer.lower() == "b":
    print("Correct!\n")
    score += 1
else:
    print("Wrong!\n")

# Question 3
print("3. What is the output of 3 + 2 * 2?")
print("a) 10\nb) 7\nc) 9\nd) 5")
answer = input("Enter your answer: ")
if answer.lower() == "b":
    print("Correct!\n")
    score += 1
else:
    print("Wrong!\n")

print("Quiz Completed!")
print("Your Score =", score, "/ 3")

if score == 3:
    print("🎉 Excellent!")
elif score == 2:
    print("😊 Good job!")
else:
    print("🙂 Keep practicing!")
