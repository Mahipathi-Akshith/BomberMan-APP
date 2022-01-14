# BomberMan-APP

A Bomberman-style game with multiplayer option
A Bomberman-style game with multiplayer option made with Phaser.js, Node.js, Express.js, Socket.io.

Game description:
The game is designed for up to three players.

Games can be played on one of two maps.

![image](https://user-images.githubusercontent.com/84834842/149459515-53209d74-2ddd-4e27-a63c-174f21c60aaa.png)

Player models user will receive randomly when he will enter the game.

The winning player is the last one standing.

Within the game, players can upgrade skills like: ( Change to drop - 50% when player break the block )

![image](https://user-images.githubusercontent.com/84834842/149459672-44874cb5-b68b-4ea6-8eda-c90101892c2e.png)  Speed: can increase to 3

![image](https://user-images.githubusercontent.com/84834842/149459756-d56afad6-4956-44c1-96cb-f5dff1e445b2.png)  Bomb setting time: can be reduced to 0.5 seconds

![image](https://user-images.githubusercontent.com/84834842/149459793-70fa2f48-fa35-4820-b97a-b7965d854046.png)  Power: no limit
Demo:
You can find a tutorial on how to make Bomberman-style games here: Tutorial (need work)

A demo of this game can be found on Heroku: Bomberman with multiplayer - Demo

Note: To play the game, you should open the browser in two separate windows. The game pauses when You open a new tab in the same window. Open game in different windows.

Game: Click to play:
![image](https://user-images.githubusercontent.com/84834842/149459984-3eb29450-d296-4aa4-b7a9-1eb46d2b0e73.png)


Menu: Click to play:
![image](https://user-images.githubusercontent.com/84834842/149460020-3b501277-a8f4-4c72-9f2b-843e9abf66e1.png)


Setup:
The game requires Node and Yarn (npm) package manager. Make sure that you already have both installed on your system before trying to launch it.

Steps:

Clone the repository.
Run yarn install inside a newly created directory.
Start the server with the command yarn run server ( defined in the package.json file ). This will launch webpack in your development environment and then start the node server.
Check out the game at http://localhost:3000
Enjoy!
Notes:
You can use my code as a boilerplate if you want, but I would suggest you change the tile sizes. I've picked tiles that are 35x35 pixels, but tiles that are 32x32 would be more ideal. All free templates are based on this tile size, and it is also handily divisible by 2.

To Debug Node process:
Open: chrome://inspect/#devices
Click 'Open dedicated DevTools for Node'
"server": "webpack --mode development && node --inspect server/app.js",
