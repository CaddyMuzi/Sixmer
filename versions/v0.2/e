# Software Title: Sixmer
# Version: V0.1.0
# Release Date: 12/25/2020
# Author: Jonathan Lee (jon@muzi.com)
# License: GPL
# ReadMe: Sixmer is a single and double-player number-guessing game. Please download the attached "log.xlsx" excel file to log game results. Contributions are welcome. Make sure to give credit to original creator when changes are made.


import random




import re

play = True
choices = list(range(1, 9))
random.shuffle(choices)
a = (choices.pop())
b = (choices.pop())
c = (choices.pop())
d = (choices.pop())
e = (choices.pop())
f = (choices.pop())
g = (choices.pop())
h = (choices.pop())

tries1 = 0
score1 = 100
hint1 = 0
tries2 = 0
score2 = 100
hint2 = 0
turn = 0

print("Welcome to Sixmer -- a game to uncover the unique six-digit number with the fewest guesses!!")

players = int(input("Please enter the number of players(1,2): "))
if players == 1:
    name1 = input("Please enter the name of Player 1: ")
if players == 2:
    name1 = input("Please enter the name of Player 1: ")
    name2 = input("Please enter the name of Player 2: ")
if players > 2:
    print("There can only be up to 2 players")
    play = False
if players < 1:
    print("There needs to be at least 1 player")
    play = False



while play:
    numberright1 = 0
    matching1 = 0
    numberright2 = 0
    matching2 = 0

    if players == 1:
        UserInput = input("please enter your six digit unique number(No Zeroes): ")
        string=str(UserInput)
        x=re.findall("0",string)
        if (x):
          print("Please don't include 0 in your number!")
          
        else:
          InputNumbers = [int(x) for x in str(UserInput)]
          x1 = InputNumbers[0]
          x2 = InputNumbers[1]
          x3 = InputNumbers[2]
          x4 = InputNumbers[3]
          x5 = InputNumbers[4]
          x6 = InputNumbers[5]
          a_list = [x1, x2, x3, x4, x5, x6]
          



          
          a_set = set(a_list)
          values = len(a_set)
          if values < 6:
              print("Please enter a six-digit unique number!")
          if values > 6:
              print("Please enter a six-digit unique number!")
          if values == 6:
              if a == x1:
                  numberright1 += 1
              if b == x2:
                  numberright1 += 1
              if c == x3:
                  numberright1 = numberright1 + 1
              if d == x4:
                  numberright1 = numberright1 + 1
              if e == x5:
                  numberright1 = numberright1 + 1
              if f == x6:
                  numberright1 = numberright1 + 1
              if x1 == a:
                  matching1 = matching1 + 1
              if x1 == b:
                  matching1 = matching1 + 1
              if x1 == c:
                  matching1 = matching1 + 1
              if x1 == d:
                  matching1 = matching1 + 1
              if x1 == e:
                  matching1 = matching1 + 1
              if x1 == f:
                  matching1 = matching1 + 1
              if x2 == a:
                  matching1 = matching1 + 1
              if x2 == b:
                  matching1 = matching1 + 1
              if x2 == c:
                  matching1 = matching1 + 1
              if x2 == d:
                  matching1 = matching1 + 1
              if x2 == e:
                  matching1 = matching1 + 1
              if x2 == f:
                  matching1 = matching1 + 1
              if x3 == a:
                  matching1 = matching1 + 1
              if x3 == b:
                  matching1 = matching1 + 1
              if x3 == c:
                  matching1 = matching1 + 1
              if x3 == d:
                  matching1 = matching1 + 1
              if x3 == e:
                  matching1 = matching1 + 1
              if x3 == f:
                  matching1 = matching1 + 1
              if x4 == a:
                  matching1 = matching1 + 1
              if x4 == b:
                  matching1 = matching1 + 1
              if x4 == c:
                  matching1 = matching1 + 1
              if x4 == d:
                  matching1 = matching1 + 1
              if x4 == e:
                  matching1 = matching1 + 1
              if x4 == f:
                  matching1 = matching1 + 1
              if x5 == a:
                  matching1 = matching1 + 1
              if x5 == b:
                  matching1 = matching1 + 1
              if x5 == c:
                  matching1 = matching1 + 1
              if x5 == d:
                  matching1 = matching1 + 1
              if x5 == e:
                  matching1 = matching1 + 1
              if x5 == f:
                  matching1 = matching1 + 1
              if x6 == a:
                  matching1 = matching1 + 1
              if x6 == b:
                  matching1 = matching1 + 1
              if x6 == c:
                  matching1 = matching1 + 1
              if x6 == d:
                  matching1 = matching1 + 1
              if x6 == e:
                  matching1 = matching1 + 1
              if x6 == f:
                  matching1 = matching1 + 1

              if numberright1 <= 5:
                  print(name1, "you got", matching1, "matching, with", numberright1, "of those in the correct places")
              if numberright1 == 6:
                  tries1 = tries1 + 1
                  print("Congratulations", name1, "! You guessed the number!")
                  print("You guessed the number in", tries1, "tries")
                  print("You scored", score1)
                  break

              again = str(input("Do you want to keep playing?(Yes or No) "))
              if again == "Yes":
                  tries1 = tries1 + 1
                  score1 = score1 / 1.1
                 
              if again == "No":
                  play = False
                  tries1 = tries1 + 1
                  print("The number was", a, b, c, d, e, f)

              if again == "no":
                  play = False
                  tries1 = tries1 + 1

                  print("The number was", a, b, c, d, e, f)

          numberfinal = str(a) + str(b) + str(c) + str(d) + str(e) + str(f)
        
        

    if players == 2:
        if turn % 2 == 0:
            input= print(name1, "please enter your six digit unique number(No Zeroes))")
            tring=str(UserInput)
            x=re.findall("0",string)
            if (x):
              print("Please don't include 0 in your number!")
            else:
          
              x1 = int(input())
              x2 = int(input())
              x3 = int(input())
              x4 = int(input())
              x5 = int(input())
              x6 = int(input())
              a_list = [x1, x2, x3, x4, x5, x6]
              a_set = set(a_list)
              values = len(a_set)
              if values < 6:
                  print("Please enter a six-digit unique number!")
              if values > 6:
                  print("Please enter a six-digit unique number!")
              if values == 6:
                  if a == x1:
                      numberright1 += 1
                  if b == x2:
                      numberright1 = numberright1 + 1
                  if c == x3:
                      numberright1 = numberright1 + 1
                  if d == x4:
                      numberright1 = numberright1 + 1
                  if e == x5:
                      numberright1 = numberright1 + 1
                  if f == x6:
                      numberright1 = numberright1 + 1
                  if x1 == a:
                      matching1 = matching1 + 1
                  if x1 == b:
                      matching1 = matching1 + 1
                  if x1 == c:
                      matching1 = matching1 + 1
                  if x1 == d:
                      matching1 = matching1 + 1
                  if x1 == e:
                      matching1 = matching1 + 1
                  if x1 == f:
                      matching1 = matching1 + 1
                  if x2 == a:
                      matching1 = matching1 + 1
                  if x2 == b:
                      matching1 = matching1 + 1
                  if x2 == c:
                      matching1 = matching1 + 1
                  if x2 == d:
                      matching1 = matching1 + 1
                  if x2 == e:
                      matching1 = matching1 + 1
                  if x2 == f:
                      matching1 = matching1 + 1
                  if x3 == a:
                      matching1 = matching1 + 1
                  if x3 == b:
                      matching1 = matching1 + 1
                  if x3 == c:
                      matching1 = matching1 + 1
                  if x3 == d:
                      matching1 = matching1 + 1
                  if x3 == e:
                      matching1 = matching1 + 1
                  if x3 == f:
                      matching1 = matching1 + 1
                  if x4 == a:
                      matching1 = matching1 + 1
                  if x4 == b:
                      matching1 = matching1 + 1
                  if x4 == c:
                      matching1 = matching1 + 1
                  if x4 == d:
                      matching1 = matching1 + 1
                  if x4 == e:
                      matching1 = matching1 + 1
                  if x4 == f:
                      matching1 = matching1 + 1
                  if x5 == a:
                      matching1 = matching1 + 1
                  if x5 == b:
                      matching1 = matching1 + 1
                  if x5 == c:
                      matching1 = matching1 + 1
                  if x5 == d:
                      matching1 = matching1 + 1
                  if x5 == e:
                      matching1 = matching1 + 1
                  if x5 == f:
                      matching1 = matching1 + 1
                  if x6 == a:
                      matching1 = matching1 + 1
                  if x6 == b:
                      matching1 = matching1 + 1
                  if x6 == c:
                      matching1 = matching1 + 1
                  if x6 == d:
                      matching1 = matching1 + 1
                  if x6 == e:
                      matching1 = matching1 + 1
                  if x6 == f:
                      matching1 = matching1 + 1

                  if numberright1 <= 5:
                      print(name1, "you got", matching1, "matching, with", numberright1, "of those in the correct places")
                  if numberright1 == 6:
                      tries1 = tries1 + 1
                      print("Congratulations", name1, "! You guessed the number first!")
                      print("You guessed the number in", tries1, "tries")
                      print("You scored", score1)
                      break

                  again = str(input("It is now Player 2's turn. Do you want to proceed?(Yes or No) "))
                  if again == "yes":
                      tries1 = tries1 + 1
                      score1 = score1 / 1.1
                      turn = turn + 1
                      print("So far, you've made", tries1, "tries, and your score is ", score1)
                  if again == "no":
                      play = False
                      tries1 = tries1 + 1
                      print("The number was", a, b, c, d, e, f)

        if turn % 2 == 1:
            print(name2, ",please enter your six digit unique number below(Press enter after each digit)")
            x1 = int(input())
            x2 = int(input())
            x3 = int(input())
            x4 = int(input())
            x5 = int(input())
            x6 = int(input())
            a_list = [x1, x2, x3, x4, x5, x6]
            a_set = set(a_list)
            values = len(a_set)
            if values < 6:
                print("Please enter a six-digit unique number!")
            if values > 6:
                print("Please enter a six-digit unique number!")
            if values == 6:

                if a == x1:
                    numberright2 += 1
                if b == x2:
                    numberright2 = numberright2 + 1
                if c == x3:
                    numberright2 = numberright2 + 1
                if d == x4:
                    numberright2 = numberright2 + 1
                if e == x5:
                    numberright2 = numberright2 + 1
                if f == x6:
                    numberright2 = numberright2 + 1
                if x1 == a:
                    matching2 = matching2 + 1
                if x1 == b:
                    matching2 = matching2 + 1
                if x1 == c:
                    matching2 = matching2 + 1
                if x1 == d:
                    matching2 = matching2 + 1
                if x1 == e:
                    matching2 = matching2 + 1
                if x1 == f:
                    matching2 = matching2 + 1
                if x2 == a:
                    matching2 = matching2 + 1
                if x2 == b:
                    matching2 = matching2 + 1
                if x2 == c:
                    matching2 = matching2 + 1
                if x2 == d:
                    matching2 = matching2 + 1
                if x2 == e:
                    matching2 = matching2 + 1
                if x2 == f:
                    matching2 = matching2 + 1
                if x3 == a:
                    matching2 = matching2 + 1
                if x3 == b:
                    matching2 = matching2 + 1
                if x3 == c:
                    matching2 = matching2 + 1
                if x3 == d:
                    matching2 = matching2 + 1
                if x3 == e:
                    matching2 = matching2 + 1
                if x3 == f:
                    matching2 = matching2 + 1
                if x4 == a:
                    matching2 = matching2 + 1
                if x4 == b:
                    matching2 = matching2 + 1
                if x4 == c:
                    matching2 = matching2 + 1
                if x4 == d:
                    matching2 = matching2 + 1
                if x4 == e:
                    matching2 = matching2 + 1
                if x4 == f:
                    matching2 = matching2 + 1
                if x5 == a:
                    matching2 = matching2 + 1
                if x5 == b:
                    matching2 = matching2 + 1
                if x5 == c:
                    matching2 = matching2 + 1
                if x5 == d:
                    matching2 = matching2 + 1
                if x5 == e:
                    matching2 = matching2 + 1
                if x5 == f:
                    matching2 = matching2 + 1
                if x6 == a:
                    matching2 = matching2 + 1
                if x6 == b:
                    matching2 = matching2 + 1
                if x6 == c:
                    matching2 = matching2 + 1
                if x6 == d:
                    matching2 = matching2 + 1
                if x6 == e:
                    matching2 = matching2 + 1
                if x6 == f:
                    matching2 = matching2 + 1

                if numberright2 <= 5:
                    print(name2, "you got", matching2, "matching, with", numberright2, "of those in the correct places")
                if numberright2 == 6:
                    tries2 = tries2 + 1
                    print("Congratulations", name2, "! You guessed the number first!")
                    print("You guessed the number in", tries2, "tries")
                    print("You scored", score2)
                    break

                again = str(input("It is now Player 1's turn. Do you want to proceed?(Yes or No) "))
                if again == "yes":
                    tries2 = tries2 + 1
                    score2 = score2 / 1.1
                    turn = turn + 1
                    print("So far, you've made", tries1, "tries, and your score is ", score1)
                if again == "no":
                    tries2 = tries2 + 1
                    play = False
                    print("The number was", a, b, c, d, e, f)

            numberfinal = str(a) + str(b) + str(c) + str(d) + str(e) + str(f)
            








