# WebGL Course Writeup

### Order of operations
* Init GL
* Create and compile vertex shader
* Create and compile fragment shader
* Create shader program
* Attach shaders to shader program
* Link and run shader program webgl context

### 3: Vertex Buffers
* Array of vertices
* Zero is center; +X is the right edge; +Y is the top
* +Z extends towards viewer
* `drawArrays`: always update 3rd param to reflect number of verts in the buffer

### 4: Drawing Arrays
* LINES: Every two verts define a line (1-2, 3-4, ...)
* LINE_STRIP: draws a series of line segments from the very first vertex to the last one
* LINE_LOOP: Like line strip, but generates line segment between  the last and the first
* TRIANLGES: Like LINES, but takes evert three points to make a filled triangle
* second param of drawArrays is the offset/starting vertex
