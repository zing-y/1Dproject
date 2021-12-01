# 1Dproject
CDT game code
print("nice")
##test
hello
testing123
hellooo
#okay HERE GOES THE ACTUAL GAME
# THE STARTING DISCRIPTION AND INTRO!
print('Would you like to start playing Smarty Pants?')

x = input("Yes or No?: ").upper()

print("------------------------------------------------------------------------------------------------------------")

while x != 'YES' and x != 'NO':
    #keep asking for input
    print('Please type in Yes or No')
    print('Would you like to start playing Smarty Pants?')
    x = input("Yes or No?: ").upper()
    
if x == "YES":
        print ('Welcome to the informative and exciting game of Smarty Pants where you can learn new things and have fun with your friend!')
        print("------------------------------------------------------------------------------------------------------------")
        
        Player_1 = input('What is the nickname that Player 1 would like to use?: ')
        Player_2 = input('What is the nickname that Player 2 would like to use?: ')
        print("------------------------------------------------------------------------------------------------------------")
    
        while Player_1 == Player_2:
            Player_2 = input('Get out!! Choose a different name from Player_1!: ')
            
        print('Hello', Player_1, "and", Player_2, "!")
        print("------------------------------------------------------------------------------------------------------------")
        
        print('Okay before we play, my name is Bartholemeow and I am the game master of Smarty Pants!')
        print('Let me now elucidate (explain) how this game goes hmph')
        print("------------------------------------------------------------------------------------------------------------")
        
        print('There will be a total of 3 rounds consisting of 5 questions each')
        print('And each round tests on 3 different subjects: Mathematics, Science, and General Knowledge')
        print("------------------------------------------------------------------------------------------------------------")
        
        print('But fret not! if you are weak in a particular subject, you are allowed to choose the difficulty level of each question asked')
        print('There are 3 different difficulty levels avaliable: EASY, MEDIUM, HARD')
        print("------------------------------------------------------------------------------------------------------------")
        
        print('Buttt, the different difficulty levels have different scores so beware!!')
        print('This is the summary of the point system: \n EASY: 1 Point \n MEDIUM: 3 Points \n HARD: 5 Points')
        print("------------------------------------------------------------------------------------------------------------")
        
        print('There is another interesting touch to this game! if your answer is wrong, there will be points dedcuted MUHAHAHAH')
        print('This is the summary of the deduction system: \n EASY: - 0 Point \n MEDIUM: - 1 Points \n HARD: - 2 Points')
        print("------------------------------------------------------------------------------------------------------------")
        
        print('At the end of the 3 rounds, all the points scored will be added together and the Smarty Pants (WINNER) will be announced')
        print("------------------------------------------------------------------------------------------------------------")

        print('OkaY', Player_1,'and', Player_2, 'LET THE BRAIN BATTLE BEGINNN!!!')
        
elif x == "NO":
    print('Aww manz! Hope you will play Smarty Pants another time!')

###################################################
print(player1.upper(),"WINS THE GAME!")

print("     ( ๑>ᴗ<๑ )")
print("      (ง'̀-'́)ง")
print("    (⌐■_■)–︻╦╤─")
print("    (づ￣ ³￣)づ")
print("    ϞϞ(๑⚈ ․̫ ⚈๑)∩")
print("CONGRATULATIONS!!!!")
#####################################################

import random
#List of questions & answers
se1 = "What % of earth is covered by water? \n  A: 71% \n  B: 69% \n  C: 78% \n  D: 64% \n"
se2 = "qfe? A: 71% \n  B: 69% \n  C: 78% \n  D: 64% \n"

#Dictionary of questions & correct answers
ls_sc_e = [{se1:"A"},{se2:"B"}]
points = 0

#marking system
randomquestion = random.randint(0,len(ls_sc_e)-1)
question_going_to_ask = ls_sc_e[randomquestion]
print(question_going_to_ask.keys())

answer input()
if input(se1).upper() == sc_e[se1]:
    points += 1
else:
    points +=0

#print score
print("Score:" ,points)



#Dictionary of questions & correct answers
sc_e = {se1:"A"}
print(sc_e)
del(sc_e[se1])
print(sc_e)

###################################################################
