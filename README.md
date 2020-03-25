# BumpSim
BumpSim is a toy app to test computational spread of a theoretical contagion. Features will be added as users request them, with effort to document algorithms used.

- Risk is an arbitrary measure of susceptibility per added node. Low slider means lower probability of passing an infection from infected to non-infected nodes. 
- Mortality is an arbitrary probability of death after the infection duration. Lower slider means lower probability of node death. 
- Duration is an arbitrary length of infection leading to either death or immunity. 
- Infected is a switch which adds an infected node if it is on. When off, the node is added without an infection. 
- Copy to Clipboard will copy two arrays: one array with a list of all nodes attributes, and another array of all node events where a node bumps into another node.
- Each node can be tracked through their UUID.

To use the app, change the sliders and press the "Add Node" button. Please note that you must add at least one Infected node to see the simulated spread of a theoretical contagion. 

Green Nodes are Healthy, Red Nodes are Infected, and Blue Nodes are Immune. If a node dies, it is removed.
