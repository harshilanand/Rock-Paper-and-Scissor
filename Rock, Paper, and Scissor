import random

choices = ['rock','paper','scissors']

while True:
    computer = random.choice(choices)
    player = None
    
    while player not in choices:
        player = input('rock paper or scissors? : ').lower()

    if player == computer:
        print('computer : ',computer)
        print('player : ',player)
        print('Tie!')

    elif player != computer:
        if player == 'rock':
            if computer == 'paper':
                print('computer : ',computer)
                print('player : ',player)
                print('Computer won !')
            elif computer == 'scissor':
                print('computer : ',computer)
                print('player : ',player)
                print('You won !')

        if player == 'paper':
            if computer == 'scissor':
                print('computer : ',computer)
                print('player : ',player)
                print('Computer won !')
            elif computer == 'rock':
                print('computer : ',computer)
                print('player : ',player)
                print('You won !')

        if player == 'scissor':
            if computer == 'rock':
                print('computer : ',computer)
                print('player : ',player)
                print('Computer won !')
            elif computer == 'paper':
                print('computer : ',computer)
                print('player : ',player)
                print('You won !')
    
    play_again = input('Do you want to play again ? (yes/no): ').lower()

    if play_again != 'yes':
        break

print('Bye!')
