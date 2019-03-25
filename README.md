# STSHeuristicsMod
 Heuristic rating based deck tracking mod for Slay the spire. 
 Upon viewing card reward screen, displays average ratings for cards in deck and displays ratings for offered cards.
 Upon adding a card to your deck, updates and displays the new average.
 
# Installation
Copy the .csv and .jar to your Slay the spire "mod" folder inside the installation directory. 
Launch the game "with mods" from steam and check the mod to activate it.

# Usage
Fill in the ratings according to your liking (hopelfully the defaults will get better with time). Here are the parameters currently used:  

## D1 (damage, single target) : Integer in range [0,10]
## Dx (damage, area of effect) : Integer in range [0,10]
## DS (damage, scaling) : Integer in range [0,10]
## M1 (mitigation, single target) : Integer in range [0,10]
## Mx (mitigation, area of effect) : Integer in range [0,10]
## MS (mitigation, scaling) : Integer in range [0,10]
## $ (Scores from SpireLogs tier list) : Integer in range [~-300,~300]

# Development
Currently uses console as interface instead of in-game gui elements. That should be fixed.
Support should be added for similar behaviour upon entering shops.
