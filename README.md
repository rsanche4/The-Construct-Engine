# THE CONSTRUCT: RAYCAST ENGINE+

SO you could do the following:
- different heights encoded in a world. Like 1 world has a height thats it. But its not fixed for every single world. So if u wanna go to a different world with different heights that wall can render that. You can have a buildings type thing, up to the sky, and then when going isnide one, then back to a small corridor.

- and now that you can also have those heights, you can also have huge tall sprites! wide sprites! Go all out with sprites! And also let sprites change their pitch so a z-axis of where they are in the world. So sprites can be as big as you want them to be.

- 360 frames for directional sprites? That could lead you to do all sorts of things like an arcade machine for example. U need blender sure and its almost like voxel territory at that point but it works.

- invisible walls (and basically solid sprites same thing, have NPCs also recognize those invisible walls as walls)

- Change the control so B is Ctrl instead. So Space, Ctrl, Enter, Arrows

- Switch up so we can travel and transfer to worlds like portals type thing so doors (just fade to balack to is fine but we need to somehow to have different maps)

- upload to new github repo and call it The Construct - Raycast Engine +

- Maybe have it so you could have multiple textures on each side of wall, that is one thing I needed for Dead Shot Girl but couldnt get around it. So just allow for multi texturing in 1 block multuple sides.

- The other thing you want to do is change from JavaSwing to OpenGL or a faster program that uses GPU or something fast like that. Cuz JavaSwing appli just takes too long.

- Now as for the editor, just fix that. It's very like weird, using txts to back things up and just slow using pygame. Might switch to something that lets us build the world easier to fix that.

- backing entire worlds data through long strings of sprite names comma seprated, not good, so way better alternative to just save binary data somehow or something thats more efficient and takes up less space. 

- Include a manual pdf, an explenation behind each design choice, and just an explenation also for the math behind raycasting and how it works etc, a release of the engine on how to use it, the executbale, open a moddb page for it if anybody is interested

- If you could do a Duke Nukem Mission 1 Clone that would be great so include that with the engine to say hey you can technically build something like this with my engine, might not be as good but it is something! And only change the level so for the part that is the cinema showcase an anime or something

- Oh also change the API so its not in screen.java but in its own class cuz that file is way too huge

- also go through the rendering logic and really make sure every component is ok and not weird or doing something that isn't needed

- Multiplayer online support so do a multiplayer map where we can shoot each other etc using the Duke Nukem assets and maybe a way to have them display on our end that works