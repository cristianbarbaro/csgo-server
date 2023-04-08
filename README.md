# csgo-server

* Edit variables with your data (get your *RCDS_TOKEN* from https://steamcommunity.com/dev/managegameservers):
  * `cp variables.env-example variables.env`
  * `cp env-example .env`
  
* Run docker compose:
  * `docker compose up -d`

* Go to http://localhost:4326 and put credentials defined in `.env` file. 

* More ENV variables https://hub.docker.com/r/cm2network/csgo.

* More info about configurating a CS:GO server:
  * https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive_Dedicated_Servers#Advanced_Configuration
  * https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive/Game_Modes
  * https://wiki.4netplayers.com/en/RCON_Commands_CSGO
