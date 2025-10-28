# rv-there-yet-gamesave

## Use save game

Navigate to
`%localappdata%\Ride\Saved\SaveGames\<id>`

Drop the two files in there

<img width="629" height="295" alt="image" src="https://github.com/user-attachments/assets/1ad460bd-99db-45a4-8763-fe2f6f0d52e3" />

## Enable more players

First, find or create the following configuration file:

`%localappdata%\Ride\Saved\Config\Windows\Game.ini`

Open the configuration file in Notepad and add the following lines:
```
[/script/engine.gamesession]
MaxPlayers=5
```
Make sure you do this while the game is closed to ensure the changes take effect the next time you launch the game.
If you want to revert it, you can simply remove the added lines.
