# Quiz-Game

print("Welcomr to the game")

playing = input("Do you want to play: ")

if playing.lower() != "yes":
    quit()

print("Okay let's play :) ")
score = 0

answer = input("What does CPU stands for: ")
if answer.lower() == "central processing unit":
    print("correct")
    score += 1
else:
    print("incorect")
    print("correct answer is = central processing unit!")

answer = input("What does GPU stands for: ")
if answer.lower() == "graphics processing unit":
    print("correct")
    score += 1
else:
    print("incorrect")
    print("correct answer is = graphics processing unit!")

answer = input("What does RAM stands for: ")
if answer.lower() == "random access memory":
    print("correct")
    score += 1
else:
    print("incorrect")
    print("correct answer is = random access memory")

print("you got " + str(score) + " questions correct ")
print("you got " + str((score / 3) * 100) + "%")
