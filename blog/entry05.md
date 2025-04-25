# Entry 5
##### 04/25/2025

## Content
I have finished my minimum viable product and have added significantly to the game. 

The first thing that I wanted to focus on was making it so that the enemy would move back and forth. The way that I did that was I had to add conditionals so that when the enemy would reach certain objects that they would switch directions and head in the opposite direction so that they would be able to go back and forth,

<img width="767" alt="Screenshot 2025-04-25 at 2 16 34 PM" src="https://github.com/user-attachments/assets/f4ace172-8dff-4d6f-965f-6ff28af7c321" />

    
I made it so that when the enemy would make contact with a lamp, the variable `direction` they had would switch to the value of, `left`. After that I made it so that when the enemy's variable had that value, that they would have a force to make them go left,
    
<img width="773" alt="Screenshot 2025-04-25 at 2 19 58 PM" src="https://github.com/user-attachments/assets/c94ac0d3-e25e-426e-8901-a2bbf11f9f7f" />
    
Now when the enemy hits a lamp, they will go towards the left. Now I needed to make it so that the enemy would go back towards the right. To do that I added houses and when the enemy would bump into a house, the `direction` variable would have the value of `right` and then added the condition that if the value of `direction` is `right`, that the player would have a force pushing the enemy towards the right.
    
<img width="775" alt="Screenshot 2025-04-25 at 2 23 41 PM" src="https://github.com/user-attachments/assets/b327bbe9-ed46-4bcb-a715-cfd716c9fec7" />
    
    
<img width="781" alt="Screenshot 2025-04-25 at 2 23 52 PM" src="https://github.com/user-attachments/assets/2485acbb-b471-443a-9906-f452b47d1b15" />
     
Now the enemy would go back and forth,
    
<img width="1051" alt="Screenshot 2025-04-25 at 2 24 39 PM" src="https://github.com/user-attachments/assets/83d2754f-703f-4849-bfa6-32c08864137e" />
   
I then added a condition that I found on [this website](https://wiki.gdevelop.io/gdevelop5/tutorials/platformer/part-7/#step-2-kill-the-enemy) that would help me figure out how to make it so that the enemy would kill the user if the user came into contact with the enemy. 
   
<img width="727" alt="Screenshot 2025-04-25 at 2 27 43 PM" src="https://github.com/user-attachments/assets/b8866305-8ef4-460b-a3ec-eebbdc5af9fc" />
    
I had to create different scenes that the player would see if they would die or win. So I created two more scenes, the winning scene and the dead scene,
   
(Losing scene, when the player would die due to making contact with the enemy)
<img width="699" alt="Screenshot 2025-04-25 at 2 33 37 PM" src="https://github.com/user-attachments/assets/ffe5c6a8-cb78-4563-a96f-62466392edc7" />
      
(Winning scene, when the player would collect all the fruits)
<img width="695" alt="Screenshot 2025-04-25 at 2 35 20 PM" src="https://github.com/user-attachments/assets/aebfd3dd-62cb-42da-b578-9b19e0eea402" />




## EDP


## Skills
[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
