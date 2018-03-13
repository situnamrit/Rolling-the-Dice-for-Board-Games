# Rolling-the-Dice-for-Board-Games
Two Dices is Being Rolled And the output is displayed in the screen 
import random
dice1 = [1,2,3,4,5,6]
dice2 = [1,2,3,4,5,6]
print(" DICE 1 is BEING ROLLED \n")
random.shuffle(dice1)
random.shuffle(dice2)
choice = 'y'
while choice == 'y' or choice == 'Y':
     random.shuffle(dice1)
     random.shuffle(dice2)
     print(random.choice(dice1)+random.choice(dice2))
     print("DO YOU WANT TO ROLL AGAIN \n")
     choice = (input("ENTER YOUR CHOICE"))

