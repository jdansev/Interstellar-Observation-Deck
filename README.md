# 3D Space Deck (Web Experience)

Recently I've noticed that 3D related graphics (games, virtual sims, etc.) were less prevalent on the web than their desktop counterparts. The few that do, existed in the form of short demos and mini games. I was intrigued and began this project to explore the capabilities of 3D graphics on the web.

The environment is set in outer space, with some interesting moving visuals and interactive elements. I used [BabylonJS](https://www.babylonjs.com/), a 3D JavaScript engine that comes with good documentation and framework tools. I've also sourced some high quality assets from [Sketchfab](https://sketchfab.com/).

![Screenshot 1](screenshot1.png) ![Screenshot 2](screenshot2.png)

### Technologies and Tools Used
* BabylonJS
* NodeJS
* HTML, CSS, JavaScript
* Blender for editing/preparing the 3D models

### Instructions
Move: `w a s d`  
Toggle night lamp on/off: `e`  
Toggle between first person and orbit view: `c`  
Select the spaceship or the planet while in orbit mode to switch between orbit objects

### Setup
To run this project, install it locally using npm:  
```
npm install
npx http-server
```

Go to http://localhost:8080

### Requirements
* A fast GPU since BabylonJS uses WebGL
* Some patience while loading the textures and assets which could take a few minutes
