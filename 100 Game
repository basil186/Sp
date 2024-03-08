## game description
## 100 game. Two players start from 0 and alternatively add a number from 1 to 10 to the sum.
## The player who reaches 100 wins. 
 
##  NAME:                                                      ID:
##  Bassel HossamEldin Adham Abd Elaziz                    20230545



def game_100():
    sum = 0
    while sum < 100:
        player1_move = int(input("Player 1: Enter a number from 1 to 10: "))
        while player1_move < 1 or player1_move > 10:
            player1_move = int(input("Wrong Number. Please Player 1: Enter a number from 1 to 10: "))
        sum += player1_move
        print("sum is", sum)
        if sum >= 100:
            print("Player 1 wins!")
            break
        player2_move = int(input("Player 2: Enter a number from 1 to 10: "))
        while player2_move < 1 or player2_move > 10:
            player2_move = int(input("Wrong Number. Please Player 2: Enter a number from 1 to 10: "))
        sum += player2_move
        print("sum is", sum)
        if sum >= 100:
            print("Player 2 wins!")

game_100()

