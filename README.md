# FPSGameHealthSystemSimulator
 
A game simulator with two different health management systems: 
 - Standard health bar + med-kits 
 - CoD-like red tunnel vision indication of low health + regenerative health
 
This simulator served as an online lab environment for my master thesis which investigates the relationship between implemented health management system and the player's experiences.

**System 1**
Health is represented with a simple health bar in the bottom left corner of the screen:
![image](https://github.com/user-attachments/assets/d8921a5e-cbae-4490-a455-1e11b923fa3e)

Med kits appear as "+" signs in place of deeated enemies:
![image](https://github.com/user-attachments/assets/f9ff01d3-5433-4fcd-a9cd-f01080b193c8)

**System 2**
Health is represented visually by red blood-like overlay:
![image](https://github.com/user-attachments/assets/65705f0d-4464-43b2-875a-6641af7d6524)

The visibility of the overlay differs based on how low the player's health is:
![image](https://github.com/user-attachments/assets/a041dffe-8276-4b96-8119-15a08c833bb7)

Healing is done by evading anemy attacks for a brief moment. Health then regenerates automatically every secound untill the player either regenerates to full health or is damaged by the enemy.

**Other mechanics**
- Other mechanics in the game include shooting, running and jumping. 
- The simulator counts time in the upper right corner. 
- In the bottom right corner the player can see current and max ammo of his weapon.
- After player dies, he respawns in the starting points, but the enemies he defeated before do not respawn.
- The objective of the garma is to defeat all 20 enemies in each of total 3 maps.
- The player cannot progress to the next map untill he finishes the current map.
- The stats like kills, deaths and time spent on a particular map are stored, and displayed after beating every map, 
  or they can also be checked by clicking Tab.

Aiming:
![image](https://github.com/user-attachments/assets/98f68878-ed51-4fc0-a4a5-42cd490882f1)

Directional hit indicators:

![image](https://github.com/user-attachments/assets/7797324b-83cc-460b-9212-25da90ab2f5a)



