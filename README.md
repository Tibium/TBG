# TBG
Text Based Python Game

This game is very basic and modular intended to grow
\n
In the artwork script add:
\n
- def nameofyourart():
- print()
- print"yourartworkhere"
- print()
\n
In the rooms script add:
\n
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
\n  
Changing the above script will create a new room after creating a new room you need to edit the random in the changer unless its attached specificly to another room.
\n
def execute_randoms():
    rooms = [room1, empty_room]
    random.choice(rooms)()
\n
Here in the top of the rooms script youll had your room name
\n
def execute_randoms():
    rooms = [room1, empty_room, your room name]
    random.choice(rooms)()



