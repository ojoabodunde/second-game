print("welcome to my computer quiz game")

playing = input("do you want to play? ")

if playing.lower() != "yes":
    quit()

print("okay let's play ")
score = 0

answer = input ("what does CBN stands for? ")
if answer.lower()  == "central bank of nigeria":
    print("correct!")
    score += 1

else:
    print("incorrect!")


answer = input("what does CPU stands for? ")
if answer.lower() == "central processing unit":
    print("correct!")
    score += 1
else:
    print("incorrect!")

answer = input("what is the name of the president of the united state? ")
if answer.lower() == "joe biden":
    print("correct!")
    score += 1
else:
    print("incorrect!")

answer = input("how many people did moses took to the ark? ")
if answer.lower()  == "nobody":
    print("correct!")
    score += 1
else:
    print("incorrect!")

answer = input("what is the full meaning of ram? ")
if answer.lower()  == "random access memory":
    print("correct!")
    score += 1
else:
    print("incorrect!")

answer = input("state the book that recorded (jesus wept)? ")
if answer.lower()  == "john 11:35":
    print("correct!")
    score += 1
else:
    print("incorrect!")

answer = input("how many books are there in the bible? ")
if answer.lower()  == "66":
    print("correct!")
    score += 1
else:
    print("incorrect!")

answer = input("who killed Goliath? ")
if answer.lower()  == "david":
    print("correct!")
    score += 1
else:
    print("incorrect!")

print("you got " + str(score) + " questions correct!")
print("you got " + str((score / 8) * 100) + " %. ")

print("thanks for playing. cheers! ")






