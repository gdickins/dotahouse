
My app will allow people to view stats on recent games of Dota 2.

similar to www.dotabuff.com

My app will allow users to log in and view their recent played games. They will be able to see the winrate for each hero in the game as well.


https://api.steampowered.com/IDOTA2Match_570/GetMatchHistory/V001/?key=0D881FAE4289DFE70D36DF2899610719

this API shows the 25 most recent played games


Models: User, Game, Hero, Item
Collections: Users, Games, Heroes, Items
Views: GameView, PlayerView, HeroView, ItemView

A game view will contain 10 player views.
A player view will contain a hero view and several item views

Honestly the more I think about it the more this project scares me. In order to retrieve some of the data we have to also log in to the Steam services. The amount of games happening and the total number of players is absolutely huge. I'm not really sure wh
