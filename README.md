# THE CONSTRUCT: RAYCAST ENGINE+

SO you could do the following:
- different heights encoded in a world. Like 1 world has a height thats it. But its not fixed for every single world. So if u wanna go to a different world with different heights that wall can render that. You can have a buildings type thing, up to the sky, and then when going isnide one, then back to a small corridor. Secotr based build engine approach is better.

- and now that you can also have those heights, you can also have huge tall sprites! wide sprites! Go all out with sprites! And also let sprites change their pitch so a z-axis of where they are in the world. So sprites can be as big as you want them to be.

- means player also has a z axis so have that

- invisible walls (and basically solid sprites same thing, have NPCs also recognize those invisible walls as walls)

- These are the controls: 
Arrow Keys - Move / Turn
Shift + Arrow Keys - Strafe
Spacebar - Open / Interact
Enter - Same as Spacebar (backup interact)
Ctrl - Fire weapon
Alt - Reload
1 / 2 / 3 - Switch held item (gun, melee, health)
Esc - Exit / Back / Pause
PgUp - Look Up
PgDn - Look Down

- Switch up so we can travel and transfer to worlds like portals type thing so doors (just fade to balack to is fine but we need to somehow to have different maps)

- upload to new github repo and call it The Construct - Raycast Engine +

- Maybe have it so you could have multiple textures on each side of wall, that is one thing I needed for Dead Shot Girl but couldnt get around it. So just allow for multi texturing in 1 block multuple sides.

- The other thing you want to do is change from JavaSwing to OpenGL or a faster program that uses GPU or something fast like that. Cuz JavaSwing appli just takes too long.

- Now as for the editor, just fix that. It's very like weird, using txts to back things up and just slow using pygame. Might switch to something that lets us build the world easier to fix that.

- backing entire worlds data through long strings of sprite names comma seprated, not good, so way better alternative to just save binary data somehow or something thats more efficient and takes up less space. 

- Include a manual pdf, an explenation behind each design choice, and just an explenation also for the math behind raycasting and how it works etc and for my engine how its done, a release of the engine on how to use it, the executbale, open a moddb page for it if anybody is interested

- If you could do a Duke Nukem Mission 1 Clone that would be great so include that with the engine to say hey you can technically build something like this with my engine, might not be as good but it is something! And only change the level so for the part that is the cinema showcase an anime or something, or you could build DSG again with 6 missions: Rooftop, School hallways, School lobby, City, Subway, Airport. Voice acting, etc. You know the good drill. 9.99 type dollars on Steam. Include in the game key easter egg locations: arcade machines for the original DSG, Lolas World of Wonders, Iva Somnia, the Stray Sheep bar even from catherine, Leblanc from P5, and the duke nukem classic cinema screen with duke nukem arcade and maybe the screen showing some anime or something. "I dont have time to play with myself" type comment whenseeing that. English subtitles. Realistic zombie art etc. (and make it so we need to find ammo for our gun so we have limited bullets)

- Make it so that it's 512x512 for resolution, and allow for chaing height sectors so make it double or float so they can have variying heights and floor ceiling. Textures should be applied one side of wall, and they can change etc depending on what we want etc.

- Build it in C/C++ 

- Oh also change the API so its not in screen.java but in its own class cuz that file is way too huge

- also go through the rendering logic and really make sure every component is ok and not weird or doing something that isn't needed

- I guess the only question i have is how much do I want the user to mod. Personally I think the engine should just implement a first person right of the bat. Built in. Because these are the kind of experience that it can give you. You can do a walking sim basically also but it should be kept with a shooter in mind. So implement a bunch of things with that in mind. Maybe even build directly a game with it. And the engine is a mod on top of that. The point is this is the kind of games you can make with it etc.

- Try to do this by end of summer if possible

- When implementing it, also do some sort of parallel rendering so it draws things even faster