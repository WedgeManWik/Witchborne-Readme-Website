# Witchborne

Witchborne is a speed-running fast paced medieval themed First-Person Shooter parkour game Inspired by Ghost Runner and Neon White. I created this game along side six other people within 6 weeks for a University assignment.

The aim of the game is to get to the end of each level by doing parkour, avoiding traps and obstacles, killing enemies whilst trying to avoid them, collecting pickups such as arrows and coins, avoiding death at all costs, all in the shortest amount of time.
The game introduces five elements – Fire, Water, Ice, Dark and Light.
Enemies of different type of element will be resistant to and weak against different types of arrows. 
For example, an Ice golem would be weak to fire arrows making them a one shot, and resistant to ice arrows – taking no damage at all. However, some enemies are so weak that they are a one shot regardless. Headshots also do double the damage to enemies.
In total, there are seven levels including the tutorial level. Each of the levels is themed around an element and has unique aesthetics to the others.

I was responsible for creating the following levels:

## Normal Level

This was the first level which I created for the game. It starts off simple, in a narrow hallway where the player just has to move and duck to avoid hitting obstacles, and then gets to a harder section where the level has a couple different paths the player can take, with harder parkour jumps. 
This level also includes gates and doors which open in specific events like the player killing the first dragon in the level or going in front of the door.
![Normal Level](https://github.com/WedgeManWik/Witchborne-Readme-Website/blob/main/NormalLevel.png?raw=true)

## Water Level

This is the second level which I created. Visually and functionally I feel like it’s on another level to the first level, as it has a lot of epic scenery using waterfalls and a dungeon inside an underwater cave. It’s the first map of the game which is themed around a specific element. It is also the first level of the game which has traps in it.
This map is bigger and wider than the first and has more routes you can take.
![Water Level](https://github.com/WedgeManWik/Witchborne-Readme-Website/blob/main/WaterLevel.png?raw=true)

## Light Level

This is the third level which I created. 
It is located in the sky, has multiple paths the player can take, as well as hidden ones.
Coming up with the idea for this map was very difficult as I had no clue what a light level would really include, but I think I chose the right direction for it, and it looks amazing.
![Light Level](https://github.com/WedgeManWik/Witchborne-Readme-Website/blob/main/LightLevel.png?raw=true)

## Ice Level

The ice level is the latest level which I created, and is definitely my most proud level. It has the most paths and sub-routes the player can take out of all the levels, it has traps unique to the level (falling icicles) and just an awesome aesthetic. And also a unique door which is opened by shooting an icicle attached to a chain.
It has a hidden cave which the player can go down as an easter egg.
![Ice Level](https://github.com/WedgeManWik/Witchborne-Readme-Website/blob/main/IceLevel.png?raw=true)

As well as Level design, I was also rsponsible for:

## Player hand and camera animations

To make the movement of the player seem faster and more fluid, I added animations for the player’s hand moving up and down depending on their speed, as well as making it so that the player’s hand sways to the side when the player strafes. 

Another thing which I implemented was camera animations – the camera rotates whenever the player wall runs, and increases its field of view depending on how fast the player is going. This makes it seem like the player is actually going faster than they are.
The code which I’ve written, makes it so the animations are smooth, so that the player’s FOV doesn’t just suddenly jump up to its max, the camera doesn’t just suddenly rotate 10 degrees when the player is wall running and the player’s hand doesn’t just teleport up and down.
Shooting mechanic for crossbow and cannons
for the shooting of the crossbow, Instead of firing at the same trajectory each time, the arrow shot from the crossbow will fly in an arc trajectory and go to wherever the player’s cursor is pointing to.
And as for the cannons, they Aim ahead of the player if in line of sight and rotate themselves towards the player to shoot. The cannon balls are also shot in an arc trajectory.


