to start this project run `npm run dev`

- all materials are shader materials either written by us or pre-written by threejs.
- the vertex shaders are ran first then the fragment shaders.

### The sin Function

- only has values between -1 and 1.

### Other Notes about Vertex Shaders

- vertex shaders are ran each vertices.
- use uniforms to animate objects in a 3d space.
- shaders are ran in parallel on the GPU. Making these shader animations a better choice with performance in mind.
- use `varying` to get numbers from the vertex shader into the fragment shader.
