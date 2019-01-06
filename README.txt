Prerequisites: 
1. League v4.20 client: https://mega.nz/#!hpkiQK5A!pFkZJtxCMQktJf4umplAdPC_Fukt0xgMfO7g3bGp1Io
2. A brain with some experience with code.

For it to work: 
Go into GameServer folder,
then GameServerConsole,
then bin,
then Debug,
then Settings,
open GameServerSettings.json,
then change "clientLocation" to the path to your deploy folder that is inside League-420 folder (MAKE SURE TO CHANGE \ TO /).

If you have no Settings folder:
Skip to step "To run",
then go to "For it to work"

To run:
Go into GameServer folder,
then GameServerConsole,
then bin,
then Debug,
then run GameServerConsole.exe and it will auto-launch League (ONLY for Player 1).

To run as player 2:
Go into your deploy folder that is inside League-420 folder,
then move run p2.bat file inside deploy folder,
then run GameServerConsole.exe,
then open run p2.bat.

Commands:
In-game, type !help for a list.

To change character:
Go into GameServer folder,
then GameServerConsole,
then bin,
then Debug,
then Settings,
then open GameInfo.json and change whatever settings you want (try not to mess with runes as the wrong ID will crash your game).

To add/delete a player:
Go into GameServer folder,
then GameServerConsole,
then bin,
then Debug,
then Settings,
then open GameInfo.json and highlight:
What yours might look like:
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
} <=(this is where you add the ,)

then add , next to the } at the end to notify the game you have more players than 1,
then paste the info you copied with Ctrl+V and change the name to a new name, etc.
When you want to delete, just select what you copied, delete it, then delete the , next to the } from before.

If you want to use Custom League Content:
Download League 4.20 client,
then go into Custom League Content folder,
then drag League of Legends folder to your League of Legends 4.20 folder.
