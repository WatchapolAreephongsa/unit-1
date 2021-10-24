# Unit 1: A classic game 
![game](https://user-images.githubusercontent.com/82266864/138603002-17cc4a82-0dbb-49b6-889f-7842dbc692ea.gif)

# Criteria A: Planning

## Problem definition

The owner of the local game shop is an enthusiast of classic computer games. He has been looking for a talented programmer that can help him revive his passion for text-based games. He has few requirements for this task:

1. The game has to be entirely text-based.
2. The game must record the time played.
3. The game must record the player name and score.

Apart for this requirements, the owner is open to any type of game, topic or genre.

## Proposed Solution
### Design Statement:
I will design and make a game for a client who is The owner of the local game shop. The game will be an RPG/story game about surviving in the killing game which its concept is inspired by the series "Squid Game", this game will be conduct using Pycharm. It willa month weeks to make and evaluate according to the success criteria below.

### Tools/ Structure Justification
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In this project I will use python to create the text base game because of 3 main reasons. First of all, python is a very simple coding language compared to others. Therefore, creating a python program will take less time ,so that we can finish the final product by the time given by the client. Moreover, due to python simplicity which most of the python codes are based on English language, it's easy to understand the code and point out some mistakes or error made during the process. Secondly, despite the fact that python is very simple coding language, it also have the versatility and efficiency, python has many modules and functions which allows the creator to use it in many ways. In this project, the module time and functions for database will be use to record the player's data include name, score, time, etc which will meet the client's second and third requirements. Finally, python is the text-based coding language which mean that most of the time, python's output will be text and this meet the client's first requirement for the game to be entirely text-based.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In this project, I will use PyCharm as the platform to create the game because PyCharm is one of the platform that allows python coding and PyCharm also has many supportive functions that help the user with many things such as pointing out user's error which will or might cause the system error. Moreover, PyCharm also allow the user to create many types of file not just .py for python but also .txt for text which help with player's record database.In addition, PyCharm is also very organized that it will sort files in user's project by name or other things depends on user's setting which allow the users to easily find and create new files for their projects. From the reason mentioned above, PyCharm is a very suitable platform for making any python's project especially for this project which we need to use .txt and many different files to create the game. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Lastly, the game that I will create is the story game which I chose this kind of game because story game does not have the specific group of customers and it is very easy for anyone to understand how to enjoy the game play and story at the sametime ,since the client is the local game shop which their customer can be anyone from any age group and gender. Therefore, the concept of the game that I chose is inspired from the "Squid Game" which is the series that's very famous in every age group.

## Success Criteria

Client's
- The game has to be entirely text-based.
- The game must record the time played
- The game must record the player’s name and score.

My own criteria
- Choice game
   - Allow player to  change story and endings depends on their choice
- Story game
   - Based on Series squid game
   - Survival game
- Has 7 chapters 
   - Each chapter will have different games.



# Criteria B: Design

## System Diagram

![IMG_2F0D75F8BEB2-1](https://user-images.githubusercontent.com/82266864/135953524-507fe1af-f51b-48ba-82ed-0afa2cd38b9c.jpeg)
**Figure 1.** System diagram for the proposed solution

As shown in **Fig. 1**, the proposed solution runs on Python and it is developed using Pycharm (v. 2021). The proposed game, "DNG" will be able to save player's name, score and time and it will allow the player to select the difficulty and save their check point when they die. This game will be code on software macOS BigSur Ver.11.4.


![IMG_D4B5286D405F-1](https://user-images.githubusercontent.com/82266864/138593212-a40dbba5-4448-4a36-bd69-cfb775092c65.jpeg)

**Figure 2.** System diagram for the proposed solution

As shown in **Fig. 2**, the proposed solution runs on Python 3.9 and it is developed using Pycharm (v. 2021). The proposed game, "ISAK Game" will be able to save player's name, score, time and it will save player's final status when the player die or when the player complete the game. This game will be code on software macOS BigSur Ver.11.4 on MacBook Air 2020.


## Flow Diagrams
### Ceasars Cypher

![Encoder (2)](https://user-images.githubusercontent.com/82266864/138595140-22cbbec8-4053-4536-90b7-15733c19e6df.png)
**Figure 3.** Flow Diagram for encoder


___________________________________________________________________________________________________________________________________________________________________


![Encoder (1)](https://user-images.githubusercontent.com/82266864/138595112-57116999-375e-400d-8c33-466c5cb016a9.png)

**Figure 4.** Flow Diagram for decoder

The database in the game has to be protected so that personal data is not exposed. To solve this requirement I am using the Caesar cypher. Fig. 3/ Fig. 4 shows the flow diagram for this function.

### Game

![letter](https://user-images.githubusercontent.com/82266864/138603350-fe16aa33-f1cd-41e5-9587-16cdb5352612.png)

**Figure 5.** Flow Diagram for function letter

This function is use to print some words or sentence, letter by letter with an inputted amount of delay per character.

## Record of Tasks
| Task No | Planned Action                                                  | Planned Outcome                                                                                                   | Time estimate | Target completion date | Criterion |
|---------|-----------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|---------------|------------------------|-----------|
| 1       | Write down Design Statement.                                    | Has Design statement(250 words) with justification.                                                               | 30 minutes    | 20 September           | A         |
| 2       | Write down extra success criteria.                              | Has 3 extra success criteria for the game                                                                         | 5 minutes     | 22 September           | A         |
| 3       | Create function to get player's name.                           | Function that asks for player's name and confirmation.                                                            | 15 minutes    | 23 September           | C         |
| 4       | Record Player's name in the database.                           | The game can record the player's name in the database and can read it.                                            | 1 hour        | 23 September           | C         |
| 5       | Create System Diagram for the game.                             | The system diagram can show the basic information of the system to create the game.                               | 20 minutes    | 23 September           | B         |
| 6       | Try to measure the time play using "Import time".               | The game can show the time played by player.                                                                      | 30 minutes    | 25 September           | C         |
| 7       | Create a function for encoding the database.                    | A function tested that encodes the database.                                                                      | 40 minutes    | 7 October              | C         |
| 8       | Unit Test:function for encoding with the Caesar cypher.         | To check that the function works as expected. Test with input "hello" and key = 1. The outcome should be "ifmmp". | 5 minutes     | 7 October              | E         |
| 9       | Create a function for decoding from the database.               | A function tested that decodes the player's name from database.                                                   | 20 minutes    | 8 October              | C         |
| 10      | Unit Test:function for decoding with the Caesar cypher.         | To check that the function works as expected. Test with input "ifmmp" and key = 1. The outcome should be "hello". | 5 minutes     | 8 October              | E         |
| 11      | Update new design statement and success criteria.               | New sets of success criteria and design statement that fit the new plan.                                          | 20 minutes    | 9 October              | A         |
| 12      | Create function to clear the screen.                            | The function can clear the screen using clear from os.                                                            | 5 minutes     | 10 October             | C         |
| 13      | Create function to print word letter by letter                  | The function can print the inputted word letter by letter with inputted amount of delay per character             | 20 minutes    | 10 October             | C         |
| 14      | Create function for delay.                                      | Create the function to slowdown some process(output)                                                              | 10 minutes    | 10 October             | C         |
| 15      | Create function for player to press enter to continue.          | Create function that will continue the program once the player press enter.                                       | 10 minutes    | 11 October             | C         |
| 16      | Create MVP(Chapter 1).                                          | First usable product for client to test and give feedback before continue to develop the game.                    | 2 days        | 15 October             | C         |
| 17      | Unit Test: MVP alpha test.                                      | Test the MVP to see the bug and mistakes made in order to fix it.                                                 | 1 hour        | 15 October             | E         |
| 18      | Make MVP explanation video                                      | Video to explain to client about the basic information of the game and show how the game work.                    | 1 hour        | 15 October             | B         |
| 19      | Work on Record of Tasks.                                        | Work on the record of task, update it and plan the future action to make this game.                               | 3 hours       | 15 October             | A         |
| 20      | Create new system diagram for new plan.                         | New system diagram that shows each part from the software to module and database of the new game.                 | 1 hour        | 16 October             | B         |
| 21      | Create flow diagram for encoder.                                | Flow chart diagram that shows how the secret encoder work.                                                        | 30 minutes    | 16 October             | B         |
| 22      | Create flow diagram for decoder                                 | Flow chart diagram that shows how the decoder work.                                                               | 10 minutes    | 16 October             | B         |
| 23      | Update the code for database.                                   | Put information about player's final status and show time in exact minutes and seconds.                           | 10 minutes    | 17 October             | C         |
| 24      | Create the function to record player information when they die. | The function that will record the player information and show Game over screen when the player dies.              | 40 minutes    | 17 October             | C         |
| 25      | Code chapter 2-4.                                               | Create the story after the MVP and put them together.                                                             | 1 day         | 17 October             | C         |
| 26      | Unit test: Chapter 1(MVP) - 4                                   | Test the code that I have right now to see mistakes made and to see the transition between chapters.              | 30 minutes    | 17 October             | E         |
| 27      | Code until the end(Chapter 5-7).                                | Finish the first version of the game.                                                                             | 2 days        | 18 October             | C         |
| 28      | Update Record of Tasks.                                         | Update record of task and planning.                                                                               | 20 minutes    | 18 October             | A         |
| 29      | Create code that allows player to go to any chapter they want.  | Players can play any chapter they want.                                                                           | 2 hours       | 20 October             | C         |
| 30      | Unit test: First version alpha test.                            | Test the final product.                                                                                           | 2 hours       | 24 October             | E         |
| 31      | Revise and finish all the planning stage.                       | Complete the whole planning include planning and design.                                                          | 3 hours       | 24 October             | A         |
| 32      | Ask 3 people to try the game.                                   | Get feedback from other people(Both computer science students and not) to improve the game.                       | 1 week        | 30 October             | E         |
| 33      | Fix according to feedback recieved.                             | Change some parts of the code using the feedbacks from others.                                                    | 1 day         | 31 October             | C         |


## MVP
```py

#Note: To play this game, player needs to go to the file name which is at the top right
#corner and click "edit Configurations" and click to turn on "Emulate terminal in output console" and click apply to enable os function
from Encoder import secret_encoder
from Decoder import decoder
import random
import time
import os
def clear():
    os.system('clear')
def sleep():
    time.sleep(1.5)
def slep(sleeptime):
    time.sleep(sleeptime)
Start = input("Please press 'ENTER' to start the game.")
clear()
def enter():
    sleep()
    print()
    enter = input('press ENTER to continue')
    clear()
def letter(msg,howlongyougonnasleep):
    for i in range(len(msg)):
        print(msg[i], end = '')
        time.sleep(howlongyougonnasleep)
    print()
def p():
    print()
from Name import name
k = name()

start = time.time()
time.sleep(0.5)
player_num = random.randint(1,456)
n = []
score = 0
n.append(player_num)
clear()
letter("ISAK GAME", 0.4)

print("Presented by United World College International School of Asia K____ Nihon (UWC ISAK JAPAN)")
slep(3.2)
clear()

print('It is a rainy night.')
print('')
for i in range(3):
    time.sleep(0.5)
    print('Knock!')
print()
slep(1)
print(f"Stranger A: Open your door!!!")
slep(2)
clear()
choice = int(input('''A stranger asked you to open your door, what you want to do!

Enter 1 to open your door.
Enter 2 to lock your door.
Enter 3 to escape through window.
>'''))
while choice > 3 or choice < 1:
    choice = int(input('''Enter 1 to open your door.
    Enter 2 to lock your door.
    Enter 3 to escape through window.
    (Enter only 1,2 or 3'''))
clear()
if choice == 1:
    time.sleep(1)
    print("A guy in black suit came to you with a baseball bat!")
    slep(3)
    print()
    print("Black Suit Guy: Give my money back or die!! ")
    print()
    slep(2)
    print("You owe a mafia boss 200 million yen because you bought too many grilled cheese from CK.")
    slep(3)
    enter()
    clear()
    print('5 minutes later', end='')
    letter("...", 0.2)
    sleep()
    print('The guy used baseball bat to hit you and now you are bleeding .')
    slep(3)
    print()
    print("Black Suit Guy: I will come back again tomorrow!!")
    enter()
    clear()
if choice == 2:
    print("You locked the door.")
    sleep()
    letter('BOOM!!',0.5)
    print("A guy in black suit breaks into your room with a baseball bat!")
    slep(3)
    print()
    print("Black Suit Guy: Give my money back or die!! ")
    print()
    slep(2)
    print("You owe a mafia boss 200 million yen because you bought too many grilled cheese from CK.")
    slep(3)
    enter()
    clear()
    print('5 minutes later', end='')
    letter("...", 0.2)
    sleep()
    print('The guy used baseball bat to hit you and now you are bleeding .')
    slep(3)
    print()
    print("Black Suit Guy: I will come back again tomorrow!!")
    enter()
    clear()

if choice == 3:
    print('You escaped through the window!')
    slep(2)
    print("A guy in black suit follows you with a baseball bat!")
    sleep()
    print()
    print('You tripped')
    slep(1)
    print("The guy in black suit caught you")
    slep(3)
    print()
    print("Black Suit Guy: Give my money back or die!! ")
    print()
    slep(2)
    print("You owe a mafia boss 200 million yen because you bought too many grilled cheese from CK.")
    slep(3)
    enter()
    clear()
    print('5 minutes later', end='')
    letter("...", 0.2)
    sleep()
    print('The guy used baseball bat to hit you and now you are bleeding .')
    slep(3)
    print()
    print("Black Suit Guy: I will come back again tomorrow!!")
    enter()
    clear()
print('You walk to combini to get some bandages.')
slep(1.5)
print('Stranger: Hey YOU!!')
slep(1.5)
print('You ignored')
slep(1.5)
print(f"Stranger: Hey {k}!")
slep(1)
print("A stranger called you.")
slep(1.5)
print("Stranger: Wanna play a game?")
sleep()
print()
ans = input("Type 'Y' to accept the game or type 'N' to decline.")
while ans != 'Y' and ans != 'N':
    ans = input("Type Y to accept the game or type N to decline.(Please use capital Y for yes and capital N for no)")
clear()
if ans == 'N':
    print("If you win this game you will get 100.000 yen!")
    slep(0.5)
    print()
    ans = input("Type 'Y' to accept the game or type 'N' to decline.")
    clear()
    if ans == 'N':
        print(f'I know you {k}, and I also know that you have 200 million yen debt.')
        print()
        sleep()
        print("You really don't wanna play?")
        print()
        sleep()
        ans = input("Type 'Y' to accept the game or type 'N' to decline.")
        clear()
        while ans == 'N':
            num = random.randint(1,3)
            if num == 1:
                print('Just play it!')
                print()
                sleep()
                print('Free',end = ' ')
                letter('MONEY',0.2)
                print()
                ans = input("Type 'Y' to accept the game or type 'N' to decline.")
                clear()
            if num ==2:
                print('If you lose I will just slap you!')
                print()
                sleep()
                print("You won't lose", end=' ')
                letter('any money', 0.2)
                print()
                ans = input("Type 'Y' to accept the game or type 'N' to decline.")
                clear()
            if num == 3:
                print("If you play, you can pay the mafia boss tomorrow!!")
                print()
                sleep()
                letter("JUST AN EASY GAME!",0.2)
                print()
                ans = input("Type 'Y' to accept the game or type 'N' to decline.")
                clear()
if ans == 'Y':
    print("Stranger: Let me introduce myself.")
    p()
    slep(1.5)
    print('My name is', end= ' ')
    letter("Jam",0.2)
    p()
    sleep()
    print("The game we gonna play is ",end = '')
    letter('Rock-Paper-Scissor',0.2)
    slep(2)
    print('If you win you get 100k yen but if you lose, I will slap you.')
    sleep()
    print("You can try again as many time as you want until you win.")
    p()
    idk = input("Press 'Enter' to play Rock-Paper-Scissor")
    clear()
    win = 0
    while win == 0:
        rps = random.randint(1,3)
        yr = int(input('''
        Enter 1 for rock
        Enter 2 for scissor
        Enter 3 for paper
        >'''))
        sign = ['Rock', 'Scissor', 'Paper']
        yr_sign = sign[yr-1]
        rps_sign = sign [rps-1]

        if rps == 1 and yr == 2 or rps == 2 and yr == 3 or rps == 3 and yr == 1:
            print(f"Your opponent played {rps_sign}.")
            sleep()
            print(f"You played {yr_sign}.")
            slep(3)
            print("You lost!")
            sleep()
            letter("SLAP!!",0.5)
            sleep()
            ta = input("ENTER to try again.")
            clear()

        if rps == 2 and yr == 1 or rps == 3 and yr == 2 or rps ==1 and yr ==3:
            print(f"Your opponent played {rps_sign}.")
            sleep()
            print(f"You played {yr_sign}.")
            sleep()
            print("You won!")
            p()
            sleep()
            print("You get 100k yen.")
            score += 100000
            win+=1
        if rps == yr:
            print(f"Both of you played {rps_sign}, it was a draw")
            slep(2.5)
            clear()
slep(3)
print("The guy gives you a business card with the logo: ",)
slep(2)
print('''                                                                                
                                                                                
                /%%%#%%#(//(%%%%#%#            ##%#%%%#//(#%#%%%%/              
             %%##      .(,(.(, .  ,#%%(    #%%%.             ((  #%%#           
          #%%, (#((.*.,(  *(/ ##(#.   /  %%%           .,  #####((# *%%#        
        /##  *(##########(##  .(##(    %#%          #*  (###########  .%%*      
       %%%       #####((  #   ##      ##  /%      #/#(###############,  %%%     
      #%%        ############        %%,  *%%  .#*((##############((( .  %%(    
      %%         #######(,          /%%    %%*  (. /*,#(############ ,    %%    
      %%          .##  (            %%/    ##%,(#######*##.*((*##(        %%    
      %%             (# .           #%%    %#/.##########(.  ,  .. ,      %%    
      %%%              ###(#         ##   .%%      #####(            ,   #%#    
       #%*             ,####(#,      ,%#  #%        ((## #       /###*  #%%     
        %%%             #(##            (%%         .(/            . / %#%      
          %%%           ((            (%%/                           #%%        
            %%%%        *.         (%%#   .#%%/                   %%#%          
               (#%%%%/.      *#%%%#%          %#%#%#,      ./%#%%%/             
                     ,/#%%%%(*                      *(%%%%#/,                 ''')
enter()
clear()
print("There is a phone number at the back of the card.")
sleep()
print("Jam: If you want more money", end = ' ')
slep(1)
for i in range (3):
    msg = '...'
    print(msg[i], end = '')
    slep(0.5)
slep(1)
print(' you need to learn how to take an action in the face of discomfort. Just call this number.')
p()
enter()

print('You are very broke and you want more grilled cheese, so you decided to call the number.')
slep(3)
print("Girl1: Hello.")
sleep()
print("You: I want to join the game.")
sleep()
print('Girl1: Can I have your name?')
p()
yourname = input("Please write your name.")
clear()
numberoftime = 0
while yourname != k:
    yourname = input("Please write your name CORRECTLY!")
    clear()
    numberoftime += 1
    if numberoftime == 3:
        yourname = k
        print(f"Girl1: I guess you have brain tumor or alzheimer. Your name is {k}.")
        enter()
print("Girl1: Please come to street on ISAK hill tonight. There will be an ISAK bus waiting for you.")
sleep()
walk = input("Please press 'ENTER' to walk to the bus at night.")
print()
print('You get on the bus!')
slep(2)
print('There is some smoke coming from the air conditioner.')
p()
sleep()
print('You fall asleep',end='')
letter('...',0.4)
enter()
print(f"Hello {k}, you are now player number {player_num}.")
clear()
letter("WELCOME TO ISAK GAME!!",0.51)
slep(3)
end = time.time()
timetaken = end - start
timetaken = int(timetaken)
print(f"You took {timetaken//60} minutes and {timetaken%60} seconds to complete the first chapter. Congratulation!")
slep(3)
with open('PlayerRecord-Encoded.txt', "a") as file:
    name = secret_encoder(3, k)
    file.write(f"{name},{score},{timetaken}\n")
scoreboard = int(input("Enter 1 to check scoreboard and enter 0 to skip "))
if scoreboard ==1:
    print()
    print()
    print("Scoreboard:")
    with open("PlayerRecord-Encoded.txt", "r") as file:
        for line in file.readlines():
            name, score, timetaken,  = line.split(',')
            timetaken = int(timetaken)
            print(f'''
    Player:{decoder(3, name)}    Score:{score}         Time:{timetaken//60} minutes {timetaken%60} seconds''')
    enter()
print("END of First Chapter:Debt")

```
Final Product(Working)
