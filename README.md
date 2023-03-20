# rws-chess
Project consists of two modules:
### `mediator`
This module holds list of active players and supports exchange of JSON-messages between them using web sockets. It is written on Go. It uses port 3016. In order to start it you have to go to the diectory `mediator` and execute command `go run .` or assemble project by command `go build` and run command `./mediator`.

### `client`
This module supports ReactJS application, which gets list of avaiable players, starts game, supports chess boards, pieces, list of moves and determines state of the game. It is written on NodeJS. It works on port 3006. First go to the the directory `client`. If there is no subdirectory `node_modules`, run command `npm install`. Then run command `npm start`. URL of access to game from local system is http://localhost:3006. Every open page starts new player.