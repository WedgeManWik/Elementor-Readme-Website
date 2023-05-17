# Elementor

Creating my first Unreal Engine 5 game in C++.

![Elementor](https://github.com/WedgeManWik/Elementor-Readme-Website/blob/main/ElementorCover.png?raw=true)

This game was created for one of my end of year University assignments. We were learning and getting introduced to using Unreal Engine 5, which I found to be a very interesting learning experience. With the various tools provided by Unreal, help from lecturers and some video tutorials I managed to create this game in 13 weeks.

## Game Description 

### Playing the game

#### Some basic rules
The player is spawned in a map which is a floating island in the sky, and is trying to kill as many enemies as they can, collect as many gold orbs as they can, whilst trying to survive. The game introduces three elements: fire, water and ice. 

Fire is affective to Ice, and weak against Water.

Water is affective against Fire, and weak against Ice.

Ice is affective against Water, and weak to Fire.

Throughout the map, enemies of various elements are spawned, and will attack the player with the element type of which they are. The player, can switch between elements, and shoot elemental projectiles at the enemies. As well as this, the player can activate a shield, which can also change element. The player can block elemental projectiles by switching to the correct shield type. However, firing projectiles and having the shield activated will use up the player's mana, which slowly regenerates. 

#### The Enemies

Enemies of various elements are spawned throughout the map, and it is up to the player to defeat them. Projectiles usually damage the enemies to 50% of their health; however, the player can instantly kill enemies by shooting the elemental projectile which is afective against the enemy's projectile. The enemies will roam around aimlessly until they spot the player, and will then begin to chase the player and fire projectiles at them.

#### Player Info & Controls

The player is a wizard who can cast spells of different element types. 

The player can move around the map by using the “W”, “A”, "S" and “D” keys, Space bar to jump (the player can also double jump), left mouse click to fire a projectile, right mouse click to activate their shield, "Q" to dash to the left, "E" to dash to the right, "1" to select the fire element, "2" to select the water element, and "3" to select the ice element.

The player may only fire their weapon when their shield is not active.

The player will collect points when killing enemies and collecting the golden orbs placed around the map.
