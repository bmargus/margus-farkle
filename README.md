# Margus Farkle

Multiplayer family dice game for 2–3 players.

## Deploy on Render

1. Create a **new GitHub repository** named `margus-farkle` and upload `package.json`, `server.js`, and the `public` folder containing `index.html`.
2. In Render, choose **New > Web Service**, connect the GitHub repository.
3. Choose **Node** as runtime, **npm install** as build command, and **npm start** as start command.
4. After deployment is live, open the Render URL, create a room, and share the five-letter code with the other players.

## Run locally

`npm install` then `npm start`; open http://localhost:3000.

## Notes

Room data is held in server memory. A Render restart clears ongoing games. If a player disconnects during play, their turn is skipped. Players cannot rejoin a game once it starts; start a new room if needed. Dice rolls and scoring are validated by the server. No accounts required.
