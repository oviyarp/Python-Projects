# Python-Projects
Paper Scissor Rock script
#Ex 4.17
#To program scissor-rock-paper game:
#Oviya Ramachandran Pavanan
#09/26/2021

import random

#give user input
user = eval(input("scissor (0), rock (1), paper (2): "))

computer = random.randint(0,2)

if(computer == 0 and user == 0):
    print("computer is scissor. you are scissor too. its a draw")
if( computer == 0 and user == 1):
        print("computer is scissor. you are rock. you won")
if(computer == 0 and user == 2):
    print("computer is scissor. you are paper. you won")
if(computer == 1 and user == 0):
    print("computer is rock. you are scissor. computer won")
if(computer == 1 and user == 1):
        print("computer is rock. you are rock too. its a draw")
if(computer == 1 and user == 2):
    print("computer is rock. you are paper. you won")
if(computer == 2 and user == 0):
    print("computer is paper. you are scissor. you won")
if(computer == 2 and user == 1):
    print("computer is paper. you are rock. computer won")
if(computer == 2 and user == 2):
    print("computer is paper. you are paper too. its a draw")
