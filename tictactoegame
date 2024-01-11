tictactoe = [['_','_','_'],
             ['_','_','_'],
             ['_','_','_']]
def board():
    for row in tictactoe:
        print(row)
board()
def Xplace(ask, ask2):
    while ask > 3 or ask2 > 3:
        print("Try again...")
        return False
    if tictactoe[ask - 1][ask2 - 1] == "X" or tictactoe[ask - 1][ask2 - 1] == "O":
        print("Try again...")
        return False
    else:
        tictactoe[ask-1][ask2-1] = 'X'
        return True
def Oplace(ask3, ask4):
    while ask3 > 3 or ask4 > 3:
        print("Try again...")
        return False

    if tictactoe[ask3 - 1][ask4 - 1] == "X" or tictactoe[ask3 - 1][ask4 - 1] == "O":
        print("Try again...")
        return False
    else:
        tictactoe[ask3-1][ask4-1] = 'O'
        return True

counter = 0
while True:
    ask = int(input("What row do you want to place your X on?: "))
    ask2 = int(input("What column do you want to place your X on?: "))
    while not Xplace(ask, ask2):
        ask = int(input("What row do you want to place your X on?: "))
        ask2 = int(input("What column do you want to place your X on?: "))
    if tictactoe[0] == ['X', 'X', 'X']:
        print("X has won!")
        board()
        break
    if tictactoe[1] == ['X', 'X', 'X']:
        print("X has won!")
        board()
        break
    if tictactoe[2] == ['X', 'X', 'X']:
        print("X has won!")
        board()
        break
    if [row[0] for row in tictactoe] == ['X', 'X', 'X']:
        print("X has won!")
        board()
        break
    if [row[1] for row in tictactoe] == ['X', 'X', 'X']:
        print("X has won!")
        board()
        break
    if [row[2] for row in tictactoe] == ['X', 'X', 'X']:
        print("X has won!")
        board()
        break
    if [tictactoe[0][0], tictactoe[1][1], tictactoe[2][2]] == ['X', 'X', 'X']:
        print("X has won!")
        board()
        break
    if [tictactoe[0][2], tictactoe[1][1], tictactoe[2][0]] == ['X', 'X', 'X']:
        print("X has won!")
        board()
        break
    counter += 1
    if counter == 9:
        print("It is a tie!")
        board()
        break
    board()
    ask3 = int(input("What row do you want to place your O on?: "))
    ask4 = int(input("What column do you want to place your O on?: "))
    while not Oplace(ask3, ask4):
        ask3 = int(input("What row do you want to place your O on?: "))
        ask4 = int(input("What column do you want to place your O on?: "))
    if tictactoe[0] == ['O', 'O', 'O']:
        print("O has won!")
        board()
        break
    if tictactoe[1] == ['O', 'O', 'O']:
        print("O has won!")
        board()
        break
    if tictactoe[2] == ['O', 'O', 'O']:
        print("O has won!")
        board()
        break
    if tictactoe[0][0] == ['O', 'O', 'O']:
        print("O has won!")
        board()
        break
    if [row[0] for row in tictactoe] == ['O', 'O', 'O']:
        print("O has won!")
        board()
        break
    if [row[1] for row in tictactoe] == ['O', 'O', 'O']:
        print("O has won!")
        board()
        break
    if [row[2] for row in tictactoe] == ['O', 'O', 'O']:
        print("O has won!")
        board()
        break
    if [tictactoe[0][0], tictactoe[1][1], tictactoe[2][2]] == ['O', 'O', 'O']:
        print("O has won!")
        board()
        break
    if [tictactoe[0][2], tictactoe[1][1], tictactoe[2][0]] == ['O', 'O', 'O']:
        print("O has won!")
        board()
        break
    counter += 1
    board()
