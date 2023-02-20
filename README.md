# Witchborne

Witchborne is a speed-running fast paced medieval themed First-Person Shooter parkour game Inspired by Ghost Runner and Neon White.

The aim of the game is to get to the end of each level by doing parkour, avoiding traps and obstacles, killing enemies whilst trying to avoid them, collecting pickups such as arrows and coins, avoiding death at all costs, all in the shortest amount of time.
The game introduces five elements – Fire, Water, Ice, Dark and Light.
Enemies of different type of element will be resistant to and weak against different types of arrows. 
For example, an Ice golem would be weak to fire arrows making them a one shot, and resistant to ice arrows – taking no damage at all. However, some enemies are so weak that they are a one shot regardless. Headshots also do double the damage to enemies.
In total, there are seven levels including the tutorial level. Each of the levels is themed around an element and has unique aesthetics to the others.

Normal Level
![Normal Level](https://github.com/WedgeManWik/Witchborne-Readme-Website/blob/main/NormalLevel.png)
This was the first level which I created for the game. It starts off simple, in a narrow hallway where the player just has to move and duck to avoid hitting obstacles, and then gets to a harder section where the level has a couple different paths the player can take, with harder parkour jumps. 
This level also includes gates and doors which open in specific events like the player killing the first dragon in the level or going in front of the door.

Water Level
![Water Level](https://github.com/WedgeManWik/Witchborne-Readme-Website/blob/main/WaterLevel.png)
This is the second level which I created. Visually and functionally I feel like it’s on another level to the first level, as it has a lot of epic scenery using waterfalls and a dungeon inside an underwater cave. It’s the first map of the game which is themed around a specific element. It is also the first level of the game which has traps in it.
This map is bigger and wider than the first and has more routes you can take.

Light Level
![Light Level](https://github.com/WedgeManWik/Witchborne-Readme-Website/blob/main/LightLevel.png)
This is the third level which I created. 
It is located in the sky, has multiple paths the player can take, as well as hidden ones.
Coming up with the idea for this map was very difficult as I had no clue what a light level would really include, but I think I chose the right direction for it, and it looks amazing.

Ice Level
![Normal Level](https://github.com/WedgeManWik/Witchborne-Readme-Website/blob/main/IcelLevel.png)
The ice level is the latest level which I created, and is definitely my most proud level. It has the most paths and sub-routes the player can take out of all the levels, it has traps unique to the level (falling icicles) and just an awesome aesthetic. And also a unique door which is opened by shooting an icicle attached to a chain.
It has a hidden cave which the player can go down as an easter egg.

Player hand and camera animations
To make the movement of the player seem faster and more fluid, I added animations for the player’s hand moving up and down depending on their speed, as well as making it so that the player’s hand sways to the side when the player strafes. 
Another thing which I implemented was camera animations – the camera rotates whenever the player wall runs, and increases its field of view depending on how fast the player is going. This makes it seem like the player is actually going faster than they are.
The code which I’ve written, makes it so the animations are smooth, so that the player’s FOV doesn’t just suddenly jump up to its max, the camera doesn’t just suddenly rotate 10 degrees when the player is wall running and the player’s hand doesn’t just teleport up and down.
Shooting mechanic for crossbow and cannons
for the shooting of the crossbow, Instead of firing at the same trajectory each time, the arrow shot from the crossbow will fly in an arc trajectory and go to wherever the player’s cursor is pointing to.
And as for the cannons, they Aim ahead of the player if in line of sight and rotate themselves towards the player to shoot. The cannon balls are also shot in an arc trajectory.

/////////////////////////////

I created this game for one of my University assignments. We were learning and getting introduced to using Unity, which I found to be a very interesting learning experience. With the various tools provided by Unity, help from lecturers and some video tutorials I managed to create this game in 11 weeks.

## Game Description 

Silent Night is a Japanese-style Top-Down single-player Stealth game. 
The player’s aim is to sneak through a fort filled with enemy guards in aim to get to the Main Boss and  assassinate him - the player has been given a time limit of 10 minutes to find the boss and kill him.
The player can use various things like bushes and drain systems to sneak around the map to help with not getting spotted.

### The Story

You, Shimamoto Masaru have been tasked with killing Reiko Kobayashi who has been the main source of murder crimes and gang violence in Japan in the last five years.
Reiko Kobayashi is the leader of a gang called “Blood Rain”, and their fortress is located in the mountains of Honshu. You are to assassinate him as soon as possible whilst also attracting minimal attention to yourself.

Shimamoto Masaru has wanted to avenge his parents’ death ever since he was a teenager. His parents were murdered by the Blood Rain gang, and Shimamoto has wanted revenge ever since.
In order to give himself the best chances of succeeding, he has joined the members of the “Shadow Realm”, who are a small group of assassins who practice in ancient martial arts, swordsman skills and have learned how to excrete and consume power from Ethereal Crystals, which are purple crystals that form high up in mountains.

Ethereal Crystals form in mountainous areas, and are formed when there is a large amount of blood gathered up in the soil of the ground. 
To be able to consume them and be able to use their power, the consumer’s body needs sufficient training  and modifications. Years of training needs to be spent to build up the body so it can sustain the effects of the power surge the crystals give, and modifications including the removal of parts of the brain which are needed for happiness, love, and joy are also necessary. Shimamoto has put himself through this pain, and sacrificed almost everything to adapt his body for assassination and give himself the best chances of killing Reiko.

The Blood Rain Fortress is located high up in the mountains, and inside the fortress a lot of executions and murders are committed, so it’s an ideal location for Ethereal crystals to form.

### Playing the game

#### Player Info & Controls

Player Movement is controlled with a mouse, right clicking on the ground will make the player move to that location.

The player has four attacks: 

Basic Attack - Q

Fast Attack - W

Power Attack - E

Ultimate Attack - R


Each of these attacks has their unique characteristics, and are useful in their own special cases:

The Basic attack is best for situations where the player is low on mana and needs to kill an enemy who is attacking them, as it has an extremely quick cooldown, executes quickly and has the highest damage per mana out of all the attacks.
The Fast attack can be used by the player to either close the distance or gain the distance between the enemy, as the player launches forwards when they execute this attack.
The Power attack deals a big amount of damage, so it is best used as the first strike to greatly hurt the enemy quickly.
The Ultimate attack can be used for sneak attacks from bushes to instantly assassinate the enemy. It has an extremely high mana cost however, and it is a charged attack so the player needs to wait about a second for it to be executed.

#### Player Interactions with the map

By walking into a bush, the player can hide themselves from the enemy guards. If a guard walks near the player whilst they’re inside a bush, the guard will not notice the player; however, if the player was already spotted when they went into the bush, the guard will still continue to attack the player.
There are various drain systems plotted around the map which the player can use to move underneath the ground to another location. The player can just simply walk onto a drain cover and they’ll be moved to an exit of that drainage system. This can be used to progress quickly to the next area of the map without being spotted.
The player can also walk into the ethereal crystals to collect them. these will give the player a temporary power surge, which means the player will have unlimited mana and immortality during the power surge.

#### Player Interactions with the enemies

The player can attack enemies, and by doing so - damage them. The player will gain 10 points upon damaging an enemy, and will gain an extra 50 points for killing it. However, whilst the player is spotted by enemies, the player’s points will rapidly decrease – the player will lose 2 points per second of being spotted, meaning the faster you can kill the enemies and the less time you can be spotted by them, the better.
The player Is detected one second after the enemy has gotten sight of them – giving them a more realistic and human reaction time, also meaning the enemy doesn’t start attacking you the millisecond you’re in their sight. This allows for stealth kills where the player walks out of a bush to kill an enemy.
If an enemy loses sight of the player for more than five seconds, they will stop chasing the player and go back to their guarding position, or if they’re a patrol guard, they will go back to their patrol route.
If the player is spotted by the main boss, their points are not deducted. This is because the player has to be spotted by the boss for an epic boss fight.

#### Enemy Types

Basic Guards:
These enemies are the most basic type; they stand still and guard an area, and will go attack the player if spotted.  They have 100 HP and deal 10 damage to the player per attack, and attack at about once per second. If they lose sight of the player for more than 5 seconds, they will go back to where they were guarding.
Patrol Guards:
These enemies are the exact same as the basic guards; however, they have a patrol route. The patrol guards will constantly follow a patrol route around the map, unless they spot the player. If the patrol guard loses sight of the player, it will go back to patrolling.
The Boss:
The main boss is located at the last part of the map. It has 200 HP and has two attacks which it keeps alternating between.

