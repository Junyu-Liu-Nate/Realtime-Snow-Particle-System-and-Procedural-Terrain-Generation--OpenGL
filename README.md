# Realtime Snow Particle System and Procedural Terrain Generation - OpenGL 

![Alt text](img/top.jpg)

**Brown University CSCI 1230/2230 Computer Graphics Final Project.**

**Group Name: Cyber Mountaineering Expedition**

**Keywords:** procedural terrain generation, particle system, physical collision system, solar system

## Get started

- CMake with ```CMakeLists.txt```, build, and run the source code.
- Load the ```standard_view.json``` scenefile. After loading the scenefile, there is a default terrain showing on the screen.
  ![Alt text](img/terrain_1.jpg)
- If one wnats to load different height maps as terrain, click **Upload Height Map** button and select a height map image.
  ![Alt text](img/terrain_2.jpg)

## Key features Explained

### Terrain generation

Terrain Generator allows creating volumetric mountains that can be viewed from various angles and distances.

- **Generation from height maps**: Terrain Generator forms terrain based on height map images. Users may upload any images to produce landscapes with distinctive looks.
  ![Alt text](img/terrain_3.jpg)
- **Adjust bumpiness**: Users can adjust terrain bumpiness in real-time using a slider, enabling a smoother or more rugged appearance in the generated terrain.
  ![Alt text](img/terrain_4.jpg)

### Particle system

![Alt text](img/particle_1.jpg)

- **Adjust the speed**:
  ![Alt text](img/particle_2.jpg)
- **Adjust the intensity**:
  ![Alt text](img/particle_3.jpg)

### Collision detection

The snow accumulation system calculates the real snow-terrain collision and change the visual appearance of terrain to emulate the accumulation of snow. There are three modes:

- **Default mode**: The collision point on the terrain will gradually become white.
  ![Alt text](img/collision_1.jpg)
- **Snow Physical Accumulation** clicked: Snowflake will stop and physically accumulate on the terrain to emulate the fine-grained snow accumulation. Note that depend on different computer hardware capabilities, too much accumulation may affect frame rates.
  ![Alt text](img/collision_2.jpg)
- **Snow Increase Terrain** clicked: The collision point on the terrain will gradually increase to emulate real snow accumulation. Note that such increase would be more observable by zooming in or waiting for more snow accumulation.
  ![Alt text](img/collision_3.jpg)

### Solar system

The solar system emulates the 24-hour sun movement.
![Alt text](img/solar_1.jpg)

- **Change Time** toggled: By toggling, one can change the current time. The sun will automatically move on from the toggled time.
  ![Alt text](img/solar_2.jpg)
- **Sun Moving** clicked: Stop or let the sun move. 
  ![Alt text](img/solar_3.jpg)

Enjoy the beauty of Computer Graphics!
![Alt text](img/bottom.jpg)
