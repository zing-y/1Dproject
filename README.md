# 1Dproject
CDT game code

#List of questions & answers
se1 = "What % of earth is covered by water? \n  A: 71% \n  B: 69% \n  C: 78% \n  D: 64% \n"
se2 = ""

#Dictionary of questions & correct answers
sc_e = {se1:"A" , se2:""}
points = 0

#marking system
if input(se1).upper() == sc_e[se1]:
    points += 1
else:
    points +=0

#print score
print("Score:" ,points)
