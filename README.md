# ReactTesting

In order to run the React file "counter-app" go through the following steps:


1. You need access to the 'npm start' command.

npm is node.js' default packaging software. You can gain access to this by
downloading any version of node.js.


2. Download the 'counter-app' folder. Change your directory to that folder
and run the command 'npm start'. Your default web browser should pop up with
the web application.



Files worth looking at:

App.js			(counter-app > src)
This is the brain of the application. This calls on the counters.jsx file.

counters.jsx	(counter-app > src > components)
This basically does generates the navbar and controls the state of the counters.
This file calls on the counter.jsx file to generate the counter mechanisms.

counter.jsx 	(counter-app > src > components)
This creates each counter component along with all of its components, i.e.
the number displau, counter tag and associated buttons.

VastLogo.png	(counter-app > src > components)
This image is used in counters.jsx to display the VaST logo in the navbar.