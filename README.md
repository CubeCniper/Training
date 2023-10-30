# Training

print("Hello Dear, we are here to practice about Python.")
gun = input("Please name your favorit Gun: ")
color = input("Please name your favorit Color: ")
ammo = int(input("How much ammo your gun have in one magazin? "))
mag = int(input("how many magazine you want to have? "))
totammo = int(mag * ammo)
enemy = int(input("The count for enemy is:"))
kill = int(input("How many bullet will kill one enemy? "))
avgammo = (enemy * kill)
print("Your will have " + color + " " + gun + " to use for your mission.")
print("In total you have " + str(totammo) + " ammo for your mission.")
if avgammo < totammo:
  print("and for " + str(enemy) + " enemy you need " + str(avgammo) + " ammo.")
  print("Good Luck with your mission Soldier")
else:
  print("but you need more ammo for your mission ")
  print("because you must use "+ str(avgammo) + " ammo.")
