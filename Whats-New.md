What’s News in version 1.1
====
**[New Features]**

- Add Shortcut “Cmd+L” for opening 2D Shader Editor
- Add Shortcut “Cmd+Return” for maximzing editor window
- Add “Copy” (Control+C) and “Paste” (Control+V)
- Add “Blend Mode” in shader node. Select from predefined blend mode in the list.

**[New Nodes]**

-  **RadialBar**  Create procedural radial bar
-  **Dithering**  Create dithering effect
-  **ColorMaskAB** Masking effect with two colors input. Output will leap between input A and B with the masking value.
-  **Comments** A resizable node which can add comments and group other nodes.
-  **Chroma Key** Replace color with backdrop color.
-  **PI Constant** Add PI constant to shader.
-  **AND** and **OR** operator node
-  **AND(&&)** and **OR(||)** logic node

**[New Examples]**

-  Radial Bar - Show 3 types of radial bar use for Unity UI
-  Dithering - Show dithering effect with build-in pattern and texture.
-  Force Field - Simple and complex version of force field
-  Teleport - Animated teleport effect for fading in object
-  Color Blending - Show different type of blending mode

**[Bug fix]**
- Improve performance for large number of nodes
- Hide inspector if editor window too small
- Layout error when mouse drag near the border of canvas
- Scrolling not respond when node inspector have scrollbar
- Format the title of properties node
- Ripple Node: incorrect graphic when negative offset.
- Easing Animation Node - Add waiting time before start