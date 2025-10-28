# rv-there-yet-gamesave

Enable more players:

First, find or create the following configuration file:

%localappdata%\Ride\Saved\Config\Windows\Game.ini

Open the configuration file in Notepad and add the following lines:

[/script/engine.gamesession]
MaxPlayers=5

Make sure you do this while the game is closed to ensure the changes take effect the next time you launch the game.
If you want to revert it, you can simply remove the added lines.
