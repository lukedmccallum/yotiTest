In order to run the website, first new keys are needed from the yoti hub to replace those in the env file, 
as well as a path to a PEM key.
Then if you have not downloaded the node_modules file you should run npm install
Then you should be able to run the website with node index.js whilst in the yotiTestFinal directory
Finally you should be able to access the website from https://localhost:9443/
Then you can verify your age via the app using the widget on the website.
Should you be above 18 it should respond 18+ otherwise it will respond "You have to be 18 to access this site".