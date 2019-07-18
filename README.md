# DMAPythonPi-top3
import random
choices = ["A", "B"]
choice2a =  random.choice(choices)
print(choice2a)

from time import sleep

name = input("What is your name?")
print("Hi", name, "the young adventurer, you have entered the ancient temple of BobTheBuilder.")
print("There are 2 different paths leading to 2 different doors, you choose the wrong one, and you die.")
print("As you're trying to figure out what happened the doors close shut behind you, making escape impossible.")
print("Now you get to choose which path you go on.")
print("Choice A: You go right.")
print("Choice B: You go left.")

my = input("Your Choice ")

if my == "Choice A":
    print("You died! Tip: If nothing's going right, go left")
    
if my == "Choice B":
    print("You survived! But not for long, inside the door you entered there is a room filled with hungry alligators that are nearly dead from hunger, but there is a way out!  There is another door on the other side of the room that you must open, but you must run through the pack of alligators waiting for you in the pond infront of you")
    print("The longer you wait and think the more deadly the alligators get")
    print("Choice A: Run through and try to break the door")
    print("Choice B: Wait and think")
    
my = input("Your Choice ")

if my == "Choice A":
    print("You died! Tip: If nothing's going right, go left")
    print("You got eaten")
    
if my == "Choice B":
    print("Nice, you can just wait for the alligators to die and then cross the room and break the door.")
    print("In the next room there is a pool of lava, and when you look around the room to see if there is something you can use to get across.")
    print("And in the corner of the room you see a iron stick and a mini trampoline, only one of them will get you across safely.")

print("Choice A: Jump on the tramapoline and try to jump across.")
print("Choice B: Use the stick and try to catapult yourself across.")

my == input("Your Choice ")
    
if my == "Chocie B":
    print("You died! Tip: If nothing's going right, go left.")
    
if my == "Choice A":
    print("You survived!, now for death parkour...")
    print("As you walk through the door you find that the next level is a death parkour, you mess up even ONCE you get impaled by spikes")
    print("For this new challenge you have to either jump up or run back.")
    print("A object is flying at you, if it hits you you fall into the spikes and die.")
    print("Choice A: You jump over it.")
    print("Choice B: You try to open the door go through the door.")
    
my == input("Your Choice ")

if my == "Choice A":
    print("You died! You couldn't react fast enough.")

if my == "Choice B":
    print("You run to the door and open it just in time to avoid being crushed against the door.")
    print("As you walk back to where you started you realize that the beginning of the parkour was out, which means...RESTART!")
    
print("Jk ur done, that was it.")

