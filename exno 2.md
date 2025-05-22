# EXP-02: Create A Player Movement Using Pawn, Collectable, Player Health And Score.
## Date:12-03-2025
## Aim:
To Create a player movement using pawn, collectible, player health and score.

## Procedure To Create and Destroy the coin:
1.Create a Blueprint Actor named BP_Coin in the Content Browser.

2.Add a Static Mesh Component and assign a coin mesh.

3.Add a Rotating Movement Component for spinning (optional).

4.Open the Blueprint and implement the OnComponentBeginOverlap event.

5.Check if the overlapping actor is the player using a Cast To Player node.

6.Destroy the coin using the Destroy Actor node on overlap.

7.Increment the player's score with a Score Variable.

8.Place multiple BP_Coin instances in the level for collection.

## Output:

![Screenshot 2025-05-20 214738](https://github.com/user-attachments/assets/72c26771-9d12-4783-a5dd-15788ecb579b)

![Screenshot 2025-05-20 214800](https://github.com/user-attachments/assets/156f26c0-eea8-41e6-b0f1-05fc0fc1bfbb)


## Procedure To Redirect to levels:
1.Place a Box Trigger in the level from the Modes panel.

2.Create a new Actor Blueprint or use the Level Blueprint for logic.

3.Add an OnActorBeginOverlap event for the Box Trigger.

4.Check if the overlapping actor is the player using Cast To Player.

5.Use the Open Level node to specify the target level.

6.Set the level name in the Open Level node.

7.Test the trigger by overlapping with the player character.

8.Ensure seamless transition by saving both levels properly.

## Output:
![Screenshot 2025-05-20 214924](https://github.com/user-attachments/assets/a38371af-5e0f-4f36-be14-36abbff1e4b2)

![Screenshot 2025-05-20 214941](https://github.com/user-attachments/assets/654434d6-eff6-47c8-a45c-7e0788188364)


## Result:
Thus, To Create a player movement using pawn, collectible, player health, and score created and developed by unreal Engine.
