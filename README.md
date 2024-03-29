# This is a simple text-based adventure game implemented in Java. The game provides a basic storyline where the player interacts with various characters and makes choices that affect the outcome of the game.

To run the game, execute the main method in the Game class.

The game starts with the player setting up their character. The player's health points (HP) and weapon are initialized. The player is prompted to enter their name, and then the game begins.

The game consists of different locations or scenarios that the player can navigate through. Each location presents different options or choices for the player to select.

# Here is a brief overview of the game flow:

playerSetUp: This method initializes the player's HP, monster's HP, and player's weapon. It prompts the player to enter their name and displays a welcome message.

townGate: The player arrives at the town gate and encounters a guard. The player is presented with options to talk to the guard, attack the guard, or leave. Depending on the choice, different outcomes occur.

crossRoad: The player reaches a crossroad where they can choose to go in different directions (north, east, south, or west). Each direction leads to a different scenario.

kuzey: If the player chooses to go north, they find a river and replenish their HP.

doğu: If the player chooses to go east, they discover a sharp sword, which becomes their new weapon.

batı: If the player chooses to go west, they encounter a goblin with a silver ring. The player can choose to fight the goblin or retreat.

savaş: If the player chooses to fight the goblin, a battle sequence occurs. The player and the goblin take turns attacking each other until one of them loses all HP.

kazandın: If the player defeats the goblin, they acquire the silver ring and can continue their journey.

oyunSonu: If the player returns to the guard at the town gate with the silver ring, they are welcomed into the town, and the game ends.

öl(d)ün: If the player's HP reaches zero during a battle, they lose the game.

Throughout the game, the player's choices determine the outcome and progression of the story. Some choices may lead to favorable results, while others may have negative consequences.

The game is played through a console interface. Instructions and prompts are displayed, and the player can enter their choices using the keyboard.

Feel free to modify the game or add new features to make it more interesting and immersive. Enjoy playing and exploring different paths and outcomes!
