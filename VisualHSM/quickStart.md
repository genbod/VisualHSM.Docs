# Quick Start

This is a step by step tutorial for creating your first hierarchical state machine.

# Create A Game State Machine

A Game State Machine Object is a visual representation of the states and transitions for a given state machine that can be used in your game. The same Game State Machine object can be reused across all of your scenes and can be used as a substate in other Game State Machine Objects

> Because the Game State Machine Object is loaded at runtime, it needs to be saved in a "Resources" folder

1. Right click in the project view and select: `Create / VisualHSM / Game State Machine`. As noted earlier, make sure you are saving under a "Resources" directory

2. Double-click on your newly created Game State Machine Object and the Visual HSM Editor Window should open up

![VisualHSM Editor Window](media/Visual%20HSM%20Editor%20Window.png)

This represents your newly created Game State Machine. We will go over the different parts later but for now, you can see that your Game State Machine is empty because you have no states or transitions yet.

# Add States

Without any states your Game State Machine doesn't really do much. Let's start by adding a few states.

1. Right click in the Visual HSM Editor Window and select `Add State`.

2. Right click the new state node that you just added and selet `Rename State`

3. In the dialog window that just popped up under `New Name` type `Starting State` the press `OK`

![Adding Starting State](media/Adding%20Starting%20State.png)
