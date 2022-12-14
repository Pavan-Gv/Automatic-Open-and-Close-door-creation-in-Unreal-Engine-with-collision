### Automatic-Open-and-Close-door-creation-in-Unreal-Engine-with-collision

### Aim:
To Create Automatic open and close door in Unreal Engine with collision.

### Procedure:
Step 1: Begin by creating a New > Games > Blank > Blueprint project with Starter Content enabled named TimelineDoorActor.</br>
Step 2: Click the Add/Import button to create a new Blueprint Actor class named BP_DoorActor.</br>
Step 3: Double-click the BP_Door Actor from the Content Browser to open it in the Blueprint Editor and open the Class Defaults.</br>
Step 4: Next, from the Components tab click the Add Component button and select Static Mesh to add a new Static Mesh Component.</br>
Step 5: Right-click your static mesh component and select Rename to rename it to DoorFrame.</br>
Step 6: Next, from the Components tab click the Add Component button and select Static Mesh to add a new Static Mesh Component. (Repeating step 3)</br>
Step 7: Right-click your static mesh component and select Rename to rename it to Door.</br>
Step 8: Click Add Component, select Box Collision from the dropdown menu, and rename it to Box.</br>
Step 9: Next, open the Event Graph, right-clickthe graph, and choose Add Timeline from the Blueprint Context Menu. Name your Timeline.</br>
Step 10: Begin by double-clicking the DoorTimelineComponent in the Event Graph to open the Timeline Editor.</br>
Step 11: Click Add Float Curve to add a new curve to the track and name the curve DoorRotation</br>
Step 12: Shift select both your keys, right-click, and from the Key Interpolation dropdown menu select Auto interpolation.</br>
Step 13: Save your float track.</br>

### Output
![gp5](https://user-images.githubusercontent.com/94827772/207648706-2a14fca8-e989-4af1-acd9-c9e5ee987982.jpg)

### Result
Therefore automatic open and close door in unreal engine with collision is created.
