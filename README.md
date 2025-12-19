# Feather: A Three.JS Visualization Project & Tribute to Nujabes
### Developed by Steven Carr for UMass Boston's Computer Science Graphics' course
_________________________
# Table of Contents
1. [Project Overview](#project-overview)
2. [Demo](#demo)
3. [Features](#features)
4. [Technical Details](#technical-details)
_________________________
## Project Overview
For our course, we had to choose between two "tracks": a track based on the UMass Boston Nursing Caves or a track based on the WNDR Museum in Boston - this project is based on the exhibits seen at the WNDR Museum.  Specifically, there was an exhibit I believe named "Inside Out", where you sit in a simulated house and experience weather effects all around you.  I enjoyed how the weather effects were simulated with different WebGL visual elements and wanted to take certain inspirations from it.  I had my idea for this project when listening to the artist Nujabes (Rest In Peace), specifically his song "Feather" and I came up with an idea to have a bird flying through a sky while this song plays in the background, to try to visualize the feeling that his music and specifically this song evokes in me.
_________________________
## Demo
The picture below is what the scene will look like on the initial load, with clouds, a sun and a "clear sly".  The small UI control panel in the top-left corner denotes what the user is able to do in our scene.
<img width="1920" height="913" alt="DemoLoadedPic" src="https://github.com/user-attachments/assets/21185a0e-7869-4c41-863f-363142a38e9d" />
After toggling "s", you can transition the scene into a snow state.
<img width="1920" height="915" alt="DemoSnowPic" src="https://github.com/user-attachments/assets/c467ded4-be97-4042-923e-ffe268d818a2" />
When toggling "r", you can transition the scene into a rainy state.
<img width="1920" height="915" alt="DemoRainPic" src="https://github.com/user-attachments/assets/ea07b23c-01ea-41ff-bc18-13a989ee17c5" />
With "t", you can transition into a state with tornadoes.
<img width="1920" height="914" alt="DemoTornadoPic" src="https://github.com/user-attachments/assets/024bd388-da33-4398-84f4-a16abc36b1e9" />
Finally, with "n", you can transition into a night scene.
<img width="1920" height="913" alt="DemoNightPic" src="https://github.com/user-attachments/assets/f4cb88d3-3ab8-4eff-90a3-658212967548" />
Some things that are unable to be captured with a picture: you can also toggle "m" to start playing "Feather" by Nujabes in the background, and pressing "m" mutes the music (the music keeps playing, however!).  The user can also move the bird around using their mouse location, however the positioning is based on the original camera position, so if you turn the camera around so you can view behind the bird, moving the mouse may result in weird movement of the bird - for it to be more accurate to your mouse position, you would need to face the camera back to how it loaded, which is looking ahead of the bird.  Once in any of the scene states, you can toggle that same key (if you're in a rainy state, toggle "r" again) to return back to the "clean" state, with only the clouds, sun and a "clear" sky.
_________________________
## Features
- "R" key - Rain State
- "S" key - Snow State
- "T" key - Tornado State
- "N" key - Night State
- "M" key - Music Initiation/Muting
- Mouse Controls - Mouse Icon will be hidden, but the bird will move with your mouse location based on initial camera position
_________________________
## Technical Details










