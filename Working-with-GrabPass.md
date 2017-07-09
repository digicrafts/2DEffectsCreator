GrabPass is a special pass type - it grabs the contents of the screen where the object is about to be drawn into a texture. This texture can be used in subsequent passes to do advanced image based effects.

**2D Effects Shader Editor** provide a GrabPass node which allow the shader to work with GrabPass. The GrabPass node provide a tex output which acts like normal texture node. You can sampler the tex using a Sampler2D node or use directly with nodes which support tex input.

<image>

To use GrabPass with Sample2D node.

<image>

To use GrabPass with nodes that support tex input.

<image>

