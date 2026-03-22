# Shader_Assignment
I want to get something that interacts with the mouse. Something like a conductor or someone using a theramin. I see the mouse function, I just need to get something that is noticeable and satisfying to play through. I think having the mouse be a factor adds both randomness and control to make a unique experience at each play through.

I start the performance off with a background that slowly changes through colors. To do this I added a time step to the initial color inputs within a sin wave.
The first variable in the color inputs is modified more than the others. In the background I have a function running that looks a bit like a radio wave. This function came from me browsing for interesting looking wave forms. This only presents itself when the first uncomment is made. 
The first uncomment adds in the key feature to this which is the mouse. A small white circle surrounded by a darker area of the background color, overlayed by the radio wave.
Next the radio wave is disabled to showcase the circle itself following the mouse
Then the voronoi is added to create a flowing polkadot pattern that feels magnified by the mouse. I found the voronoi function from the experiments on The Force github page and thought it would be interesting to try to incorporate.
The fourth uncomment adds a lava lamp type feel that can be pushed or pulled by the mouse. This function was discovered by just playing around with the trig functions and finding something that looked interesting.
Finally the frag function is uncommented. This creates multiple copies of the window that doesn't actually get as affected by the mouse, but still has a pleasant visual effect.
