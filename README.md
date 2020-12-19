# MuOnline

You have initial health 100 and initial bitcoins 0. You will be given a string, representing the dungeons rooms. Each room is separated with '|' (vertical bar): "room1|room2|room3…"
Each room contains a command and a number, separated by space. The command can be:
"potion"
You are healed with the number in the second part. But your health cannot exceed your initial health (100).
First print: "You healed for {amount} hp.". 
After that, print your current health: "Current health: {health} hp.".
"chest"
You've found some bitcoins, the number in the second part.
Print: "You found {amount} bitcoins."
In any other case you are facing a monster, you are going to fight. The second part of the room, contains the attack of the monster. You should remove the monster's attack from your health. 
If you are not dead (health <= 0) you've slain the monster, and you should print ("You slayed {monster}.")
If you've died, print "You died! Killed by {monster}." and your quest is over. Print the best room you`ve manage to reach: "Best room: {room}".
If you managed to go through all the rooms in the dungeon, print on the next three lines: 
"You've made it!", "Bitcoins: {bitcoins}", "Health: {health}".
