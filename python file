import random
import time
import sys

print("Rock Paper Scissors!")
print()
wep = {1: 'Rock', 2: 'Paper', 3: 'Scissors'}
opp = random.randint(1, 3)
decesion = input("> Do you want to play Rock, Paper, or Scissors? ")
while True:
    if decesion == 'Yes':
        print('Lets Play!')
        usr = input("> Choose Rock, Paper, or Scissors: ")
        time.sleep(2)
        computer = wep[opp]
        print('User chooses ' + usr + ' and the computer choses ' + computer + '!')
        time.sleep(1)
        while True:
            if usr == 'Rock' and computer == 'Rock':
                print('Draw!')
                break
            if usr == 'Paper' and computer == 'Paper':
                print('Draw!')
                break
            if usr == 'Scissors' and computer == 'Scissors':
                print('Draw!')
                break
            if usr == 'Paper' and computer == 'Rock':
                print('Paper covers Rock! User wins')
                break
            if usr == 'Scissors' and computer == 'Rock':
                print('Rock beats Scissors. Computer Wins!')
                break
            if usr == 'Rock' and computer == 'Paper':
                print('Paper bests Rock. Computer Wins!')
                break
            if usr == 'Paper' and computer == 'Scissors':
                print('Scissors beats Paper. Computer wins!')
                break
            if usr == 'Scissors' and computer == 'Paper':
                print('Scissors beats Paper. User wins!')
                break
            if usr == 'Rock' and computer == 'Scissors':
                print('Rock beats Scissors. User Wins!')
                break
            else:
                break
    if decesion == 'No':
        print(":(")
        sys.exit()
    decesion2 = input("Do you want to play again? ")
    if decesion2 == 'Yes':
        continue
    if decesion2 == 'No':
        print(":(")
        sys.exit()
    else:
        print("Please write 'Yes' or 'No'")
        break
