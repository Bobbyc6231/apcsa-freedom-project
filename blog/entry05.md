# Entry 5
##### 04/25/2025

## Content
I have finished my minimum viable product and have added significantly to the game. 

### Adding one more object to collect
I added one more fruit for the player to collect. I added a banana and just like the other fruits in the game, it would change the variable `score` to add one when the player came into contact with it.
<br/> <br/>
<img width="685" alt="Screenshot 2025-04-25 at 2 54 58 PM" src="https://github.com/user-attachments/assets/8e69a92e-d86d-4be2-8027-5a46601de663" />
<br/> <br/>
<img width="557" alt="Screenshot 2025-04-25 at 2 55 35 PM" src="https://github.com/user-attachments/assets/c0b2560a-2a01-4bba-a0f0-6a571520876e" />
<br/> <br/>

### Enemy movement
The next thing that I wanted to focus on was making it so that the enemy would move back and forth. The way that I did that was I had to add conditionals so that when the enemy would reach certain objects that they would switch directions and head in the opposite direction so that they would be able to go back and forth,
<br/> <br/>
<img width="767" alt="Screenshot 2025-04-25 at 2 16 34 PM" src="https://github.com/user-attachments/assets/f4ace172-8dff-4d6f-965f-6ff28af7c321" />
    
I made it so that when the enemy would make contact with a lamp, the variable `direction` they had would switch to the value of, `left`. After that I made it so that when the enemy's variable had that value, that they would have a force to make them go left,
<br/> <br/>
<img width="773" alt="Screenshot 2025-04-25 at 2 19 58 PM" src="https://github.com/user-attachments/assets/c94ac0d3-e25e-426e-8901-a2bbf11f9f7f" />
<br/> <br/>
Now when the enemy hits a lamp, they will go towards the left. Now I needed to make it so that the enemy would go back towards the right. To do that I added houses and when the enemy would bump into a house, the `direction` variable would have the value of `right` and then added the condition that if the value of `direction` is `right`, that the player would have a force pushing the enemy towards the right.
<br/> <br/>
<img width="775" alt="Screenshot 2025-04-25 at 2 23 41 PM" src="https://github.com/user-attachments/assets/b327bbe9-ed46-4bcb-a715-cfd716c9fec7" />
<img width="781" alt="Screenshot 2025-04-25 at 2 23 52 PM" src="https://github.com/user-attachments/assets/2485acbb-b471-443a-9906-f452b47d1b15" />
<br/> <br/>
Now the enemy would go back and forth,
<br/> <br/>
<img width="1051" alt="Screenshot 2025-04-25 at 2 24 39 PM" src="https://github.com/user-attachments/assets/83d2754f-703f-4849-bfa6-32c08864137e" />
<br/> <br/>

### Enemy damage
I then added a condition that I found on [this website](https://wiki.gdevelop.io/gdevelop5/tutorials/platformer/part-7/#step-2-kill-the-enemy) that would help me figure out how to make it so that the enemy would kill the user if the user came into contact with the enemy. 
<br/> <br/>
<img width="727" alt="Screenshot 2025-04-25 at 2 27 43 PM" src="https://github.com/user-attachments/assets/b8866305-8ef4-460b-a3ec-eebbdc5af9fc" />
<br/> <br/>

### Adding multiple scenes and changing between scenes
I had to create different scenes that the player would see if they would die or win. So I created two more scenes, the winning scene and the dead scene,

<img width="305" alt="Screenshot 2025-04-25 at 2 44 34 PM" src="https://github.com/user-attachments/assets/540f7479-f675-4667-97de-6c5a842de70d" />

<br/> <br/>
(Dead scene, when the player would die due to making contact with the enemy)
<img width="699" alt="Screenshot 2025-04-25 at 2 33 37 PM" src="https://github.com/user-attachments/assets/ffe5c6a8-cb78-4563-a96f-62466392edc7" />
<br/> <br/>
<br/> <br/>
(Winning scene, when the player would collect all the fruits)
<img width="695" alt="Screenshot 2025-04-25 at 2 35 20 PM" src="https://github.com/user-attachments/assets/aebfd3dd-62cb-42da-b578-9b19e0eea402" />
<br/> <br/>

To make the scene change throughout the game, all I did was add some conditionals so that when the player would touch the enemy, it would switch to the Dead scene,
<img width="641" alt="Screenshot 2025-04-25 at 2 47 15 PM" src="https://github.com/user-attachments/assets/7eef546a-f12d-4c2c-9972-90992767b11a" />

And when the player collected all three fruits, the global variable `score` would be three and so I made it so that when the `score` variable had the value of 3, the scene would switch to the winning scene,

<img width="695" alt="Screenshot 2025-04-25 at 2 48 49 PM" src="https://github.com/user-attachments/assets/db5dae26-fca7-40e0-93cf-07e4a561826b" />

### Changing physics of the game
The last thing that I added was conditionals so that when the player would collect the fruits, that the player's physics would change. For the apple, I changed it so that the player could jump higher and for the orange I made it so the player can't jump as high,

<img width="768" alt="Screenshot 2025-04-25 at 2 59 40 PM" src="https://github.com/user-attachments/assets/45d7e796-83ce-4fb6-9220-e8bc1593e761" />

<img width="768" alt="Screenshot 2025-04-25 at 3 00 20 PM" src="https://github.com/user-attachments/assets/c6feaa36-f092-4b38-b63a-05119135c925" />



## EDP
In the [Engineering Design Process](https://hstatsep.github.io/students/#edp) I am currently on step 5 *creating the prototype* and step 7 *improving the prototype*. Now that I have added the majority of the things that I have wanted to the game, including the objects for the player to collect, the enemy movement, the levels designs and the physics, it is time to improve the prototype. I will be adding extra stuff now to make the game more interesting such as sound effects, adding more enemies, and creating instructions to the game. From now and on, I will primarily be on step 7 in order to continue to make the game more and more enjoyable. 

## Skills
The [skills](https://hstatsep.github.io/students/#skills) that I have practiced throughout the last few weeks have been *creativity* and *logical reasoning*. I know that I am making this game for other people's entertainment so I have to try to make the game as interesting as I can. In order to do that I need to be creative with what I'm adding to the game. I originally was just going to add the fruits for the player to collect, but to make the game more enjoyable, I made it so that the physics changed when the fruits were collected. To do all of that, I needed to process many different conditionals to make it so that if something happened, something else would occur. In the examples shown above, it was that if the fruits were collected, then the physics changed or that if the player touched the enemy, they would die, and if the player would collect all the fruits, they would win. 

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)


