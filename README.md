# LeafProgram
#

#Declare Variables
windy = str()
color1 = str()
color2 = str()
leaf = str()
TotalLeaves1 = int()
TotalLeaves2 = int()
windy = input("Is it windy today (yes or no):")
color1 = input("Has your first tree turned color yet (yes or no):")
color2 = input("Has your second tree turned color yet (yes or no):")

#Tree 1 Criteria
if (windy == "no") and (color1 == "no"):
TotalLeaves1 = int(1 * 4)
elif (windy == "no") and (color1 == "yes"):
TotalLeaves1 = int(5 * 4)
elif (windy == "yes") and (color1 == "no"):
TotalLeaves1 = int(3 * 4)
elif (windy == "yes") and (color1 == "yes"):
TotalLeaves1 = int(10 * 4)

#Tree 2 Criteria
if (windy == "no") and (color2 == "no"):
TotalLeaves2 = int(1 * 4)
elif (windy == "no") and (color2 == "yes"):
TotalLeaves2 = int(5 * 4)
elif (windy == "yes") and (color2 == "no"):
TotalLeaves2 = int(3 * 4)
elif (windy == "yes") and (color2 == "yes"):
TotalLeaves2 = int(10 * 4)

print("Total Leaves lost Tree 1: ", TotalLeaves1)
print("Total Leaves lost Tree 2: ", TotalLeaves2)
