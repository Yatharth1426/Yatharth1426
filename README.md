#Rock,Paper,Scissors

import random

a=["Rock","Paper","Scissors"]

b = random.choice(a)

print("You'll be playing a game of Rock,Paper,Scissors with the computer, Good Luck!")
print("1. Rock")
print("2. Paper")
print("3. Scissors")
choice = input("Enter choice(Rock/Paper/Scissors): ")

if choice=="Rock":
    if b=="Scissors":
        print("Congrats!! You Win")
    
if choice=="Paper":
    if b=="Rock":
        print("Congrats!! You Win")
        
if choice=="Scissors":
    if b=="Paper":
        print("Congrats!! You Win")

if choice=="Rock":
    if b=="Paper":
        print("Ohh!! You Lost")
        
if choice=="Paper":
    if b=="Scissors":
        print("Ohh!! You Lost")
        
if choice=="Scissors":
    if b=="Rock":
        print("Ohh!! You Lost")

if b==choice:
    print("It's a tie")

print("The computer's choice was", b)



