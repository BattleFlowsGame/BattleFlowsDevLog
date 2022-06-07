---
title: "Dev log entry #1"
date: 2022-06-07
---

(click on title to see the full entry)

Todos (still need to be refined by priority and planned deadline)
- Improve the movement code. Troops need to flow out proportionally to the troop count in the source cell, so troops will flow much more quickly out of a full cell than a near-empty cell
- Improve the combat code. Losses for each side should be proportional to the ratio of enemy to friendly troops
- Improve the combat visuals. Currently there is no indicator when combat is happening in a cell. Draw an X across the cell to show that troops are fighting
- Add BASIC [multiplayer support](https://assetstore.unity.com/packages/tools/network/mirror-129321) to refresh knowledge on multiplayer in Unity and make sure that the game architecture is able to support it. Also remove the limitations for two players that the code currently has in some places.
- Create a tutorial that teaches players how the game works
- set up a Discord server
- consider making a TikTok account, which could be a good option according to [this ytube video](https://www.youtube.com/watch?v=YP4Aq-TrWAI)
- Terrain: have different types of cells in the hexgrid, for example hills that improve the defender and slow down movement, forests, water that can't be traversed etc.
- MORE marketing: Posts on Twitter&TikTok, learn more about indie game marketing, contact streamers that could be interested in the game etc. Yogscast is hosting a promotion for games made by small teams. The deadline is on July 17th. We could try to get into this depending on how far the game is by this point, although it looks like they require a game planned for a release on Steam. [Tiny Teams](https://www.yogscast.games/tinyteams)
- Add bases: tiles that produce troops for the player owning the hex-cell
- Fog of war. Players should only be able to see other units a certain distance away from their units
- XBattle had marching orders where troops move along a direction set by the player until encountering an obstacle. Maybe add sth. similar or path-finding that let's players give move orders for cells that are not adjacent.
- Disrupt troop flow by attacking the opponent's supply lines. Currently when combat is happening in a cell, all troop movements are paused. This lets attackers easily disrupt troop movement even with a very small amount of units. Instead, troop movement out of a cell where combat is happening should only be disrupted if the attacker has a certain amount of troops in the cell already.
- More quality of life features such as the "nospigot" option from XBattle where your troops automatically stop attacks against an overwhelming force.

Done
- [x] develop a basic version of the game, containing a useable hex grid, units, troop movement and a basic implementation of combat
- [x] set up a Twitter account for the game
- [x] dev log #1

Topics for discussion
- Graphics. The classic XBattle has very simple graphics that show clearly what is going on. They are a bit outdated for today though. It might be worthwile to add [graphical tiles](https://assetstore.unity.com/packages/2d/environments/hex-basic-set-painted-2d-terrain-52258). We still need to decide how to represent units then, although they could also remain as circles.
- Monetization. Getting some financial reward for making this game would be nice. Because of the fact that it is a) a remake of an older game and b) a multi-player game it should most likely be released as free to play, making it as easy as possible for players to get started with it. Therefore some other form of compensation would be needed. If the game is distributed on [Itch.io](https://itch.io/) we could add optional donations (or add these to whichever website the game will be hosted on). Other options? Patreon? Github Support?
- Turning it into more than "just" a remake of XBattle. Making a game with the scope and features of XBattle is something we feel comfortable that we can deliver on that promise. After the release, we could potentially build upon it by expanding the game to a different setting, add more graphics, release it on Steam etc.
- Marketing. Build up hype for the game before actually releasing it. Still need to improve this area. 

Thank you for helping me in making this game! Next dev-log entry will come by end of this week (Sunday most likely). 
