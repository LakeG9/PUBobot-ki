# Changes in this fork

Currently has a seprate leaderboard for seasons. Uses an alltime leaderboard and a seasonal leaderboard. !atlb = alltime leaderboard, !atrank for all time rank

> why

Matchmaker uses alltime rank for actually balancing games, and seasonal leaderboard can be used by staff for seasons. That way you get fair games, however you stop good players from winning every single season, and you don't let it be affected by shit like streaks and intital 10 games. Think of the seasonal leaderboard as tracking progress made by the player during the season.

# Reminder for myself on how to set up a ranked pickup

make sure:
 - ranked = 1
 - pick_teams auto
 - ranked_calibrate 1
 - (potentially) ranked_streaks 0 (Id personally disable it as players would stop queueing if they were on a streak and didn't like the players currently in queue)

# PUBobot-discord
PUBobot-discord is a multichannel discord bot for pickup games organisation.
Bot keeps statistic database, have features to automatically remove AFK users, disallow users to play pickups, fun phrases, teams picking and more!

# Requirements
Python 3.6+, sqlite3 module for python, discord api v1.0+.

# Running
1. Copy config.example.cfg as config.cfg and fill your discord bot token or username and password in it.
2. Run './pubobot.py' to launch the program.
3. Invite your bot to the desired server.
4. Type '!enable_pickups' on the desired channel.

# Getting help
You can find help or test the bot on the Pubobot developement server: https://discord.gg/rjNt9nC

# Credits
Developer: Leshka. You can contact me via e-mail leshkajm@ya.ru, on discord (Leshaka#8570) or pm 'Leshaka' on irc.quakenet.org server.   
Help: #warsow.pickup admin team.   
Special thanks to Mute and Perrina.

# License
Copyright (C) 2015 Leshka.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License version 3 as published by
the Free Software Foundation.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

See 'GNU GPLv3.txt' for GNU General Public License.
