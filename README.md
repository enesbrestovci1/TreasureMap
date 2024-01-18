# TreasureMap
print('''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.") 

print("You are at a crossroads. To the left is a dark forest, to the right is a beach")

choice1 = input("Do you want to go left or right?\n").lower()

if choice1 == "left":
  print("you have been eaten by a bear")
  sys.exit()
else:
  print("you have reached the beach safe and sound")

choice2 = input("Do you want to swim or wait?(the weather is cloudy)'\n").lower()

if choice2 == "swim":
  print("you have been eaten by a shark")
  sys.exit()
else:
  print("you are still safe")

choice3 = input("Final Stage. Enter a door: Yellow, Red, Blue\n").lower()

if choice3 == "red":
  print("You have found the treasure")
elif choice3 == "yellow":
  print("you got excecuted")
  sys.exit()
elif choice3 == "blue":
  print("you have fallen from a cliff")
  sys.exit()
else:
  print("choose a coloured door")
