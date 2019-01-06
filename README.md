# Details:
https://github.com/LeagueSandbox/GameServer and https://github.com/LeagueSandbox/LeagueSandbox-Default but with additions including more champion abilities (unfinished), custom champion files, and API functionality.

# Prerequisites:
* League v4.20 client: https://mega.nz/#!hpkiQK5A!pFkZJtxCMQktJf4umplAdPC_Fukt0xgMfO7g3bGp1Io
* A brain with some experience with code.

# Setup:
* Clone this repository (not just downloading zip)
	### Command Method:
	* `git clone https://github.com/microsoftv/LeagueSandbox-Custom`
	* `cd LeagueSandbox-Custom`
	* `git submodule init`
	* `git submodule update`
* Go into GameServer folder
* Go into GameServerConsole
* Go into bin
* Go into Debug
* Go into Settings
* Open GameServerSettings.json
* Change "clientLocation" to the path to your deploy folder that is inside League-420 folder with all \ being replaced with /.
```
C:\League-of-Legends-4-20\RADS\solutions\lol_game_client_sln\releases\0.0.1.68\deploy -> C:/League-of-Legends-4-20/RADS/solutions/lol_game_client_sln/releases/0.0.1.68/deploy
```

### Missing Settings:
* Skip to step "Running"
* After, go to "Setup"

# Running:
* Go into GameServer folder,
* Go into GameServerConsole,
* Go into bin,
* Go into Debug,
* Run GameServerConsole.exe and it will auto-launch League (ONLY for Player 1).

#### Run as P2:
* Go into your deploy folder that is inside League-420 folder,
* Move run p2.bat file inside deploy folder,
* Run GameServerConsole.exe,
* Open run p2.bat.

#### Commands:
* In-game, type !help for a list.

### Changing Character:
* Go into GameServer folder,
* Go into GameServerConsole,
* Go into bin,
* Go into Debug,
* Go into Settings,
* Open GameInfo.json and change whatever settings you want (try not to mess with runes as the wrong ID will crash your game).

### Changing Players:
* Go into GameServer folder,
* Go into GameServerConsole,
* Go into bin,
* Go into Debug,
* Go into Settings,
* Open GameInfo.json and highlight then copy:
```
{ <= this is where you start highlighting to copy)
	"rank": "DIAMOND",
	"name": "Test1",
	"champion": "Katarina",
	"team": "BLUE",
	"skin": 0,
	"summoner1": "SummonerHeal",
	"summoner2": "SummonerFlash",
	"ribbon": 2,
	"icon": 0,
	"runes": {
		//DO NOT CHANGE THESE IF YOU DONT KNOW WHAT YOU ARE DOING.
		"1": 5245,
		"2": 5245,
		"3": 5245,
		"4": 5245,
		"5": 5245,
		"6": 5245,
		"7": 5245,
		"8": 5245,
		"9": 5245,
		"10": 5317,
		"11": 5317,
		"12": 5317,
		"13": 5317,
		"14": 5317,
		"15": 5317,
		"16": 5317,
		"17": 5317,
		"18": 5317,
		"19": 5289,
		"20": 5289,
		"21": 5289,
		"22": 5289,
		"23": 5289,
		"24": 5289,
		"25": 5289,
		"26": 5289,
		"27": 5289,
		"28": 5335,
		"29": 5335,
		"30": 5335
	}
} <=(this is where you add the comma)
```

* Add a comma (,) next to the } at the end to notify the game you have more than 1 player.
* Paste the info you copied and change the name to a new name, etc.
* When you want to delete a player, just select what you copied, delete it, then delete the comma (,) next to the } from before.

# Custom League Content:
* Download League 4.20 client
* Go into Custom League Content folder
* Drag League of Legends folder to your League of Legends 4.20 folder, make sure League of Legends 4.20 folder has RADS folder.
