print("Play the rock ,paper,scissor game")
computer=input("Enter the element which you choose:")
user=input("Enter the element you choose")
if computer=="Rock"and user=="paper":
    print("Compyter chooses:",computer)
    print("User chooses:",user)
    print("Paper wins!")
elif computer=="Rock"and user=="Scissor":
    print("Compyter chooses:",computer)
    print("User chooses:",user)

    print("Rock wins!")
elif computer=="paper"and user=="Scissor":
    print("Compyter chooses:",computer)
    print("User chooses:",user)
    print("Scissor wins!") 
elif user=="Rock"and computer=="paper":
    print("Compyter chooses:",computer)
    print("User chooses:",user)
    print("Paper wins!")
elif user=="Rock"and computer=="Scissor":
    print("Compyter chooses:",computer)
    print("User chooses:",user)
    print("Rock wins!")
elif user=="paper"and computer=="Scissor":
    print("Compyter chooses:",computer)
    print("User chooses:",user)
    print("Scissor wins!") 
else:
    print("Thank you!Better luck next time...")             
