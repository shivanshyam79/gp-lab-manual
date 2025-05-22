# EXP: 07-AI CHASING
## Date: 29/04/25

## Aim:
To implement-chasing when AI see the player.

## Algorithm:
- STEP-1: Set up the AI character Blueprint and add a Sphere Collision component to the AI character Blueprint and position and scale the Sphere Collision component to represent the AI's detection range.
- STEP-2: Create a new AI controller Blueprint and select Create Basic Asset > Blueprint Class from that choose the AIController as the parent class.
- STEP-3: Open the AIController Blueprint and drag off the execution line and search for "Set Sight Radius" where the Sight Radius value to the desired range for the AI's vision.
- STEP-4: Implement perception for the AI and connect the output of the AI Perception Component node to the AI Controller's .AI Perception property in the AI Perception Component node, configure the settings for sight and sight sense
- STEP-5: Implement the chase behaviour if the stimulus is the player character, drag off the execution line and search for "Move To Actor" and set the Move To Actor node's target to the player character.
- STEP-6: Create blackboard keys for the AI and create a new blackboard object and assign it to the AIController's Blackboard property. Drag off the execution line again and search for "Create Blackboard Key".
- STEP-7: Update blackboard values. Set the Blackboard Key to the "PlayerLocation" key you created earlier.
- STEP-8: Set up the Behavior Tree by Open the Behavior Tree asset in the Behavior Tree editor.

## Output:

![image](https://github.com/user-attachments/assets/ac77ca25-7837-4f08-afa9-a3d5b5a04589)

![image](https://github.com/user-attachments/assets/8e617e1b-53a8-4b42-82aa-f73d6889fb1d)

![image](https://github.com/user-attachments/assets/559c45b9-4aa5-445d-b8f5-b6be5a9d84e0)

## Result:
Thus, the AI concept to the actor for a random movement
