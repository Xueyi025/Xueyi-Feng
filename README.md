# GDIM31 In Class Activities
## W1
When I run the game, I found that it is not in first-person view anymore. The camera stays in one place instead of moving with my cat. This is because the Camera is no longer a child of the Cat, so it does not follow the Cat’s movement.
## W2
1. Because it has decimal places in the value of r, g, b.
2. Because bounce value is integer.
3. Adding f behind the number, it keeps me reminding these numbers are using float everytime.
## W3
Activity 1（Table #12）：
1. There are two parameters, int for player’s current friendship level and bool for whether or not the player knows the character’s secret. Output is string for a character’s text response to a player’s dialogue choice.
2. There is no output saying in the prompt so the return type is void to directly edit the lightness. The parameter will be float for sanity level.
3. Parameter is float for the press time. Return type is bool, returning true if the player hits the beat correctly or false if they miss it.

Activity 2:
I think a Class is like the blueprint of PC, while a Component is like a real part installed in a computer, such as a GPU. Member variables are the properties of the GPU, like its memory size, speed, and temperature. Methods are the things the GPU can do, such as processing graphics and rendering images. Different GPUs can have different properties, but they can follow the same blueprint.

Part3:
I think the balls become extremely bright because of `ballRenderer.color *= GetColorMultiplier(...);`. Every time they bounce fast enough, their color values are multiplied by 1.5, so they keep getting brighter after many bounces.

## W4
Collision discussion activity: I added Rigidbodies to the Cat and SoccerBall because they need to move and have physical collisions. I checked Is Trigger on the Goal's Collider because I wanted the ball to pass through the goal area and trigger the OnTriggerEnter method. The Goal doesn't need a Rigidbody because the SoccerBall already has one.

Table #12:
1. I added Rigidbodies to the cat and the soccer ball. I also made sure they had Colliders. I checked Is Trigger on the Goal's Box Collider so the ball could enter the goal area and trigger the OnTriggerEnter method. I didn't check Is Trigger on the soccer ball or the ground because I wanted them to have normal physical collisions.
2. My game didn't work perfectly at first. The cat was floating above the ground, and the soccer ball was falling through the ground. I found that some of my Collider settings were incorrect. I had to adjust the cat's Capsule Collider and fix the soccer ball's Sphere Collider. I also checked the Is Trigger settings to make sure the ball could collide with the ground and enter the goal correctly.

## Link of itch
https://seoli0205.itch.io/assignment
