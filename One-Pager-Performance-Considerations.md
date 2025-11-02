**•	(10 points) Identify 3 sources of performance concerns for games similar to yours**

For games similar to mine, three sources of performance concerns are **FPS, fluidity,** and **battery drain** due to graphics, if they’re more complex/with more shaders. 

Since this is a 2D game, FPS isn’t as big of an issue, but it’s still something to be optimized especially for things like movement. You have to make sure the frames are updating matching the speed of the user’s device, otherwise a character might move faster or slower or the speed of things spawning in will be faster or slower. 

This ties into the next point, which is fluidity. Since the 2D, limited space aspect makes my game smaller than others, it means the features I do have should be optimized as best as possible. Fluidity would mean fast input and output, like starting to walk right when you press W, and stopping right when the button is released. This is a problem I had in my experimental project for the past checkpoint assignments – there was some latency in the character movement. I would like to fix that in my final game. Fluidity would also mean making sure players can click through menus smoothly, interact with items and characters without any delays, and keeping functions intuitive. 

Other mainstream café simulators like Internet Café Simulator and Coffee Shop Simulator are usually first person simulators where you see and move through the map through the player character, but I did find a game that has top down approach like mine, called Espresso Tycoon. All of those games have better graphics than mine, but Espresso Tycoon especially does a lot with lighting. From past experience playing games with shaders, even the more “simple” looking games can get heavy on the battery if there’s a lot of contrast and lighting, which is something that I’d want to implement in my game. So, battery draining or a device heating up due to graphics is also a concern of mine.

**•	(10 points) Identify at least one common strategy to address each performance concerns**

One common strategy to handle FPS issues is by using delta time when calculating movement speeds – this is what I used in my past projects to make sure things run the same on different devices. Another way is also optimizing the code to be as simple and optimized as possible, like having minimal scripts and not repeating any functions.

These strategies also tie into fluidity, especially code optimization, but also a lot of testing and adjusting settings of the objects used to feel more fluid, such as adjusting the speed of movement or animations. 

One way games handle battery draining issues is by providing different levels of graphics, so that those with higher performing devices can use the higher graphics and those with weaker devices can use the lower graphics, preventing them from overheating. Games also make sure not too many things are loaded in at once, so keeping the map simple is preferable. 

**•	(10 points) Summarize how you might use one or more such strategies for your own game and why**

One way I can handle battery draining issues is by testing how much power is drained when the game is run with specific levels of graphics. If what I have in mind is too complex, I can tone it down, but generally, since this game isn’t going to be fully complete, the graphics can be less of a priority, and I can keep them simpler. I’ll probably just leave graphics quality for the end after everything else is implemented (even if I love having pretty graphics). 

I’m definitely going to look into ways I can optimize my code while I make the game to handle any potential fluidity and FPS issues. I’m also going to maybe try out different calculations of movement to handle the latency issue while moving because it was a bit annoying in my “test” game and I would like to fix that in my actual game. 


