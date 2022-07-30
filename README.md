# Pac-Man Exercise
This application takes the real star of the Pac-Man game (Pac-Man) and only has Pac-Man by itself. Pac-Man will chomp around your browser and once it hits the edge of your screen, it'll bounce back and continue the mayhem. Reminiscent of the DVD logo bumping around the TV screen, try and see if you can find a Pac-Man who will the corner perfectly.

In this app, there is a button where the user can create anotehr Pac-Man. They can create as many as they want. The only limitation is how much your computer can handle. The data of each Pac-Man (position, velocity, direction, focus) are stored in an array. The function of the pacmen.js file is a recurring function that translates each Pac-Man's position, adjusts the stored data for each subsequent Pac-Man, determines which Pac-Man image to give the illusion of animation, and checks each Pac-Man position for collision with the browser. This is then beamed to the DOM.

## How to Run?
First, download all the files as a .zip file. Then extract the files onto a folder of your choice and load index.html into a browser. 
Click the "Add Pac-Man" button to add a Pac-Man. Click the "Start Game" button for the PacMen to start moving about the browser window. 

## Roadmap of Future Impovements
A fun improvement would be to have the various Pacmen to eat each other and grow in size. I would have to take a look at how some "fish eat fish" type games like Feeding Frenzy are programmed in order to figure this out.
A simpler improvement I could try making to add more chaos as well is to have the Pacmen bounce off of each other. 

Another fun improvement would be switching out the images of the Pac-Man with something from one of my interests.

## License Information
This exercise was created as an assignment for the MIT xPRO Full Stack Web Development program. 
