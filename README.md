# magiball

from random import randint
randNum =randint(1, 5)
print(randNum)

question = input("What is Your Question")

if (randNum == 1):
    print("You are asking me?")
elif(randNum == 2):
    print("Try again please!")
elif(randNum == 3):
    print("That is true!")
elif(randNum == 4):
    print("That is faulse.")
elif(randNum == 5):
    print("Ask me later.")
