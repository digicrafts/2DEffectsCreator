# What’s News in version 1.2.5

**\[New Features\]**

* Change name to **2D Effects Creator** and new "look & feel".
* Camera Effects Helper: Script to add camera effect with created shader effect.
* \[New Node\] FlowMap Node. Create animation effect using a flow map
* \[New Node\] FlowMap UV Node. Same as FlowMap Node but output UV which can use with procedural texture.
* \[New Node\] Vertex Color. Get the vertex colors.
* \[New Node\] Color to UV
* \[New Node\] Default UV Color
* \[New Node\] 4 Colors Gradient
* \[Node Update\] Gradient Node. Add new fill type, Angle.
* \[Node Update\] Gradient Node. Add new smoothing option
* \[Node Update\] Gradient Node. Add new port ‘ratio’ output a float to indicate the value of gradient.
* \[Node Update\] Color Blend Node. Add premultiplied alpha option

**\[Bug Fix\]**

* Preview in node not clipped when outside canvas
* Add Enable/Disable tint color in Shader Output Node
* All Distort Effects node, add separate RGBA output
* Fix DecodeColor Node output always return r channel
* When click on canvas with shift key or space key, selected node will deselected.

**\[New Examples\]**

* Fire \(Procedural realistic fire\)
* 2D water flow using flowmap
* Under Water Camera Effect 
* Old Video Camera Effect 

# What’s News in version 1.1.3

**\[Improvements\]**

* Optimise shader code for normal sprite shader
* Update examples for optimise shader code
* Add “Invert” option in ColorMask Node

**\[Bug Fix\]**

* “Material doesn't have a texture property '\_MainTex’” error when using a shader with UI without Texture input node
* Create new 2D Effect Shader from menu, rename the file, default connection will be broken.

# What’s News in version 1.1.2

**\[New Features\]**

* HDR Color Support in Color Property Node
* Add maximum window button in toolbar

**\[Bug Fix\]**

* Improve toolbar button icons
* Shader blend mode “Additive” change to “SrcAlpha One”
* Node size of Texture Property Node
* Left drag on node will move the canvas and node together
* Fix “Lighting” example

# What’s News in version 1.1.1

**\[Bug fix\]**

* Compile error when GrabPass connection deleted
* When a node selected, can’t switch editor by click on tab
* Can’t drag node if right click on the canvas

**\[Improvements\]**

* Improving wire connecting experience
* Improving icon image quality in toolbar
* Improving node graph images design \(Pro/Personal skin\)
* Editor images resource path is not hardcoded \(Can move the plugin folder anywhere\)

# What’s News in version 1.1

**\[New Features\]**

* Add Shortcut “Cmd+L” for opening 2D Shader Editor
* Add Shortcut “Cmd+Return” for maximzing editor window
* Add “Copy” \(Control+C\) and “Paste” \(Control+V\)
* Add “Blend Mode” in shader node. Select from predefined blend mode in the list.

**\[New Nodes\]**

* **RadialBar**  Create procedural radial bar
* **Dithering**  Create dithering effect
* **ColorMaskAB** Masking effect with two colors input. Output will leap between input A and B with the masking value.
* **Comments** A resizable node which can add comments and group other nodes.
* **Chroma Key** Replace color with backdrop color.
* **PI Constant** Add PI constant to shader.
* **AND** and **OR** operator node
* **AND\(&&\)** and **OR\(\|\|\)** logic node

**\[New Examples\]**

* Radial Bar - Show 3 types of radial bar use for Unity UI
* Dithering - Show dithering effect with build-in pattern and texture.
* Force Field - Simple and complex version of force field
* Teleport - Animated teleport effect for fading in object
* Color Blending - Show different type of blending mode

**\[Bug fix\]**

* Improve performance for large number of nodes
* Hide inspector if editor window too small
* Layout error when mouse drag near the border of canvas
* Scrolling not respond when node inspector have scrollbar
* Format the title of properties node
* Ripple Node: incorrect graphic when negative offset.
* Easing Animation Node - Add waiting time before start



