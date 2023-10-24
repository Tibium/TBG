# TBG
Text Based Python Game

This game is very basic and modular intended to grow

In the artwork script add:

- def nameofyourart():
- print()
- print"yourartworkhere"
- print()

In the rooms script add:
def yourroomname():
    artwork.yourartname()
    print("\n")
    print("\n")
    print("\nWhat do you do?")
    print("\n1). Go left")
    print("\n2). Go right")
    answer = input("\n> ")
    if answer == "1":
        execute_randomt()
        or
        print("\n")
    elif answer == "2":
        execute_randomb()
        or
        print("\n")
    else:
        game_over("Learn to follow instructions")
        
Changing the above script will create a new room after creating a new room you need to edit the random in the changer unless its attached specificly to another room. 
def execute_randoms():
    rooms = [room1, empty_room]
    random.choice(rooms)()
Here in the top of the rooms script youll had your room name
def execute_randoms():
    rooms = [room1, empty_room, your room name]
    random.choice(rooms)()



