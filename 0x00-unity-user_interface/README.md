### 0x00. Unity - User Interface

## Background Context
This project will go over the basics of Unity’s user interface. For this project, import Unity’s Standard Assets package from the Asset Store. Open one of the sample scenes and use it to play around with the windows, layouts, options, navigation methods, etc. covered in the reading. It’s necessary to get a feel for what tools are at your disposal and what they do before you use them! It will also make it easier to answer this project’s tasks.

The Unity project will not be used to grade this project’s tasks so don’t worry about saving it or making changes to it. You can open a scene by going to the Project window then choosing Sample Scenes then Scenes and double-clicking any scene (Car is recommended but any scene will work). While doing the reading, click on objects in the Scene window and play around with the interface to see what different tools and gizmos do.

You can also rearrange the Unity interface however you like! Just make sure you know where to find everything. :)

## Resources
Read or watch:

* [AR/VR Curriculum Track Introduction](https://intranet.hbtn.io/concepts/127)
* [Installing Unity](https://intranet.hbtn.io/concepts/88)
* [Unity Interface Overview](https://youtu.be/D7v2pjke5sc)
* [Unity Manual: Learning the interface](https://docs.unity3d.com/Manual/LearningtheInterface.html)
* [Unity Manual: The Main Windows](https://docs.unity3d.com/Manual/UsingTheEditor.html)
* [Unity Manual: Gizmos](https://docs.unity3d.com/Manual/GizmosMenu.html)
* [Unity Manual](https://docs.unity3d.com/Manual/index.html)
* [Unity Manual: Hotkeys - Note: Unity’s default hotkeys referenced in the tasks can be found in the Shortcuts Manager](https://docs.unity3d.com/Manual/UnityHotkeys.html)
* [Unity Manual: Using the Asset Store](https://docs.unity3d.com/Manual/AssetStore.html)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

# General
- How to navigate the Unity interface
- What is the Scene view
- What is the Game view
- What is the Hierarchy window
- What is the Project window
- What is the Inspector window
- What is the Console window
- What is the Toolbar
- What are the Play Buttons
- What are the Transform tools
- What are the Collab, Services, Account buttons
- What are the Layers and Layouts dropdowns
- What are Gizmos

# [0. Project Window: Adding Assets](./0-project_add_new)
* Which of the following is not a method of adding new assets or subfolders to a project?

  1. Drag and drop the new asset to the Project window
  2. File > New Asset
  3. Click on the Create menu on the left side of the Project window’s toolbar

# [1. Project Window: Filter Assets](./1-project_filter)
* What are the ways you can filter assets in the Project window toolbar?

  1. by Type or Label
  2. by Name or Value
  3. by Last Modified or Newest Created

# [2. Project Window: Hotkey](./2-project_hotkey)
* What is the hotkey to switch to the Project window?

# [3. Console Window: Hotkey](./3-console_hotkey)
* What is the hotkey to switch to the Console window?

# [4. Scene View: X Axis](./4-scene_x)
* What direction does the X axis represent?

  1. Left / Right
  2. Forward / Backward
  3. Up / Down

# [5. Scene View: Y Axis](./5-scene_y)
* What direction does the Y axis represent?

  1. Left / Right
  2. Forward / Backward
  3. Up / Down

# [6. Scene View: Z Axis](./6-scene_z)
* What direction does the Z axis represent?

  1. Left / Right
  2. Forward / Backward
  3. Up / Down

# [7. Scene View: Perspective and Isometric Views](./7-scene_perspective_isometric)
* You can toggle between Perspective and Isometric views by clicking the cube in the center of the Scene Gizmo.

A. [Image A](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/unity-viewA.jpg)

B. [Image B](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/unity-viewB.jpg)

* Which scene is in Perspective mode and which scene is in Isometric mode?

  - A = Perspective, B = Isometric
  - A = Isometric, B = Perspective

# [8. Scene View: Navigating Within Scenes](./8-scene_navigating)
* Which of the following is not a way of navigating within the Scene view?

  1. Arrow keys
  2. Flythrough mode
  3. Pressing the Play button
  4. Hand tool

# [9. Scene View: Hotkey](./9-scene_hotkey)
* What is the hotkey to switch to the Scene view?

# [10. Scene View: Hotkey - Center](./10-scene_center)
* What is the hotkey for centering the view on a GameObject?

# [11. Game View - Rendered View](./11-game_view)
* Where does the Game view get its rendered view from?

  1. The view from the Scene view
  2. The view from the player character
  3. The cameras in the game

# [12. Game View - Choose Camera](./12-game_camera)
* Which Game View toolbar menu lets you choose which camera to view from?

  1. Aspect
  2. Display
  3. Camera

# [13. Game View - Aspect Ratios](./13-game_aspect)
* Which Game View toolbar menu lets you test how your game looks with different aspect ratios?

  1. Screen
  2. Display
  3. Aspect

# [14. Game View - Zoom](./14-game_zoom)
* Which of the following is not a method of zooming in and out in the Game view?

  1. Scroll wheel
  2. Scale slider
  3. + and -

# [15. Hierarchy Window: Order](./15-hierarchy_order)
* What is the default order of objects listed in the Hierarchy window?

  1. Order of creation
  2. Alphabetical
  3. Order of last modified

# [16. Hierarchy Window: Reorder](./16-hierarchy_reorder)
* Which of the following is not a way of reordering objects in the Hierarchy window?

  1. Grouping objects as parent / child objects
  2. Modifying their position number property in the Inspector
  3. Dragging objects up and and down in the list

# [17. Hierarchy Window: Parenting](./17-hierarchy_parenting)
* What is Parenting in Unity?

  1. Adding a parent template component to an object
  2. Duplicating an object from another and linking them
  3. Grouping objects where the topmost object is the parent and the objects grouped under it are child objects

# [18. Hierarchy Window: Child Objects](./18-hierarchy_child)
* How do you create a child object?

  1. Write a script associating an object to its parent object
  2. Drag and drop child object onto parent object
  3. Edit the child object’s parent property in the Inspector

# [19. Hierarchy Window: Hotkey](./19-hierarchy_hotkey)
* What is the hotkey for switching to the Hierarchy window?

# [20. Inspector Window: GameObject Properties](./20-inspector_properties)
* How can you see the properties of a GameObject?

  1. Righ t-click on the GameObject and choose Properties from the menu
  2. Click on the GameObject’s gizmo
  3. Select the GameObject in the Hierarchy window or Scene view to view the properties in the Inspector window

# [21. Inspector Window: Script Components](./21-inspector_script_component)
* If a GameObject has a script component, which part of the script is displayed in the Inspector window?

  1. Method name
  2. Public variables
  3. Return value

# [22. Inspector Window: Multiple Windows](./22-inspector_multiple)
* Can you have more than one Inspector window open at once?

  1. Yes
  2. No

# [23. Inspector Window: Hotkey](./23-inspector_hotkey)
* What is the hotkey for switching to the Inspector window?

# [24. Toolbar: Rotate](./24-toolbar_rotate)
* Which Transform tool button rotates a GameObject?

  1. [Image 1](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformA.png)
  2. [Image 2](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformB.png)
  3. [Image 3](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformC.png)
  4. [Image 4](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformD.png)
  5. [Image 5](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformE.png)
  6. [Image 6](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformF.png)

# [25. Toolbar: Pan](./25-toolbar_pan)
* Which Transform tool button pans around the Scene?

  1. [Image 1](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformA.png)
  2. [Image 2](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformB.png)
  3. [Image 3](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformC.png)
  4. [Image 4](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformD.png)
  5. [Image 5](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformE.png)
  6. [Image 6](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformF.png)

# [26. Toolbar: Transform](./26-toolbar_transform)
* Which Transform tool button combines the Move, Rotate, and Scale tools into a single Gizmo?

  1. [Image 1](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformA.png)
  2. [Image 2](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformB.png)
  3. [Image 3](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformC.png)
  4. [Image 4](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformD.png)
  5. [Image 5](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformE.png)
  6. [Image 6](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformF.png)

# [27. Toolbar: Scale](./27-toolbar_scale)
* Which Transform tool button scales a GameObject?

  1. [Image 1](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformA.png)
  2. [Image 2](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformB.png)
  3. [Image 3](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformC.png)
  4. [Image 4](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformD.png)
  5. [Image 5](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformE.png)
  6. [Image 6](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformF.png)

# [28. Toolbar: Move](./28-toolbar_move)
* Which Transform tool button moves a GameObject?

  1. [Image 1](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformA.png)
  2. [Image 2](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformB.png)
  3. [Image 3](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformC.png)
  4. [Image 4](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformD.png)
  5. [Image 5](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformE.png)
  6. [Image 6](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformF.png)

# [29. Toolbar: Transform 2D](./29-toolbar_transform_2d)
* Which Transform tool button combines the Move, Rotate, and Scale tools into a single Gizmo specifically for 2D layouts?

  1. [Image 1](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformA.png)
  2. [Image 2](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformB.png)
  3. [Image 3](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformC.png)
  4. [Image 4](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformD.png)
  5. [Image 5](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformE.png)
  6. [Image 6](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-cs-unity/398/transformF.png)

# [30. Toolbar: View Arrangement](./30-toolbar_views)
* Which Toolbar dropdown controls the arrangement of all Views?

  1. Layers
  2. Layout
  3. Account

# [31. Toolbar: Displayed Objects](./31-toolbar_displayed_objects)
* Which Toolbar dropdown controls which objects are displayed in the Scene View?

  1. Layers
  2. Layout
  3. Account
