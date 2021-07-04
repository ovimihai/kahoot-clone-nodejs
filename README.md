# kahoot-clone-nodejs

project forked from https://github.com/ethanbrimhall/kahoot-clone-nodejs

### Changes
- added Docker deployment (node & mongo containers)
- parametrized mongodb url

### How to start

1. Clone repo ```git clone https://github.com/ovimihai/kahoot-clone-nodejs.git```
2. Start with ```bash run.sh```
3. Navigate to `http://{YOUR_HOST}:3000`
4. Create new game `http://{YOUR_HOST}:3000/create/`
5. Share to players `http://{YOUR_HOST}:3000/host/?id=x`

## Original Readme

<h3>INSTRUCTIONS:</h3>
<ol>
  <li>Install MongoDB: 'Sudo apt-get install mongodb'</li>
  <li>Start MongoDB: 'Sudo service mongodb start'</li>
  <li>Make sure all node modules have been installed listed in package.json: express, moment, mongodb, mongoose, socket.io</li>
  <li>Start Server: nodejs server/server.js</li>
</ol>
<br>
<h3>Description</h3>
<h5>This project is a kahoot clone that uses nodejs and mongodb</h5>
<h5>Multiple games can be ongoing at one time and works with many players per game</h5>
<h3>Screen Shots:</h3>
<img src="Screenshots/join.png" height="200" width="auto" alt="Player Join"/>
<img src="Screenshots/hostJoin.png" height="200" width="auto" alt="Host Lobby"/>
<img src="Screenshots/player.png" height="200" width="auto" alt="Player"/>
<img src="Screenshots/questionResults.png" height="200" width="auto" alt="Question Results"/>
<img src="Screenshots/hostQuestion.png" height="200" width="auto" alt="Host Question"/>
<img src="Screenshots/incorrect.png" height="200" width="auto" alt="Player Results"/>
