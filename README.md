# 1Dproject
CDT game code

#List of questions & answers
SE1 = "What % of earth is covered by water? \n  A: 71% \n  B: 69% \n  C: 78% \n  D: 64% \n"
SE2 = ""

#Dictionary of questions & correct answers
Sc_E = {SE1:"A" , SE2:""}
points = 0

#marking system
if input(SE1).upper() == Sc_E[SE1]:
    points += 1
else:
    points +=0

#print score
print("Score:" ,points)
