My first OpenGL game and first big project in C

All textures are 16x16 and using PICO-8 colour palette
Required dependency
OpenGl 3.3
SOIL
GLFW3

Compiling
```
cmake -S source/ -B build/
cd build
make
```

using cglm for math
https://github.com/recp/cglm

using nxjson for parsing json files
https://github.com/thestr4ng3r/nxjson

using cgltf for gltf file processing
https://github.com/jkuhlmann/cgltf

**Road Map**
[x] Character animation
[x] Collision with character
[x] Tile loading from `.json` file
[ ] Model loading from `.json` file
[ ] Collider loading from `.json` file
[ ] Per-texel lighting
[ ] HUD with hp
[ ] Simple enemy follower that on every touch is reducing hp
