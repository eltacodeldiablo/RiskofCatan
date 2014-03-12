RiskofCatan
===========

Risk meets Catan.

## Table of Contents

 - [Placing starting armies](#placing-starting-armies)
 - [Territory occupation vs control](#territory-occupation-vs-control)
 - [Controlling settlements/cities](#controlling-settlements-cities)
 - [Controlling roads](#controlling-roads)
 - [Buying and recruiting armies](#buying-and-recruiting-armies)
 - [Army movement and battle](#army-movement-and-battle)
 - [Army unit types](#army-unit-types)
 - [Elimination and Endgame](#elimination-and-endgame)

## Placing Starting Armies ##

- For each starting settlement/city, after placing your road/ship you also place one army on an adjacent unoccupied hex.
- If all nearby hexes are occupied, you may battle for the territory.
- However, the army placed first is on defense.
- After all settlements are placed, starting with the second player, all players take turns placing armies on unoccupied hexes, including the desert tile (but not water tiles) until all land tiles are occupied.
- As per Risk rules, army placement follows a simple loop: 2nd player, 3rd player, 4th player, 1st player, 2nd player, etc.
    - Do not "snake back" like you do for settlement/city placement.

## Risk of Catan's Art of War ##

- **Occupy** - You are said to occupy a territory (hex) if you have at least one standing army in the hex.
- **Control** - You are said to control a territory (hex) if you have a number of armies equal to or greater than the number of pips on the territory's number token.
    - For example, the Catan chit labeled "6" has 5 pips under the number, so you need five or more armies on that territory to fully control it.
    - The Catan chit labeled "11" only requires 2 armies to control it.
    - Deserts, and lands labeled "2" and "12" are controlled by any single army.
    - If an army has control an opponent's village is unable to obtain resources from that hex until the hex is "free" of enemy occupation.
- **Contest** - You are said to be contesting a territory (hex) if you move your army into an occupied but not controlled territory without attacking.
    - Neither armies can control this point until it at least one of the armies is eliminated.
    - No benefits can be received from the territory (hex) until contesting is resolved.
- **Liberate** - You are said to liberate a territory (hex) if you manage to reduce an opponent's army to be under the required pip number on the territory's number token.
- **Annex** - You are said to annex a settlement/city or road if you manage to control all adjacent territories (hexes).
    - Replace the annexed building with one's own color.
- **Siege** - You are said to siege a settlement/city when opponent's settlement is completely surrounded by troops that are not their own.
- **Lifting Siege** - You are said to lift siege when you build armies from the settlement/city to try to break occupation/control so long as the city is not captured.
    - The armies are placed on one adjacent hex of the settlement/city and they are immediately on offense and must fight until resolved.

## Rules About Annexed Settlements/Cities ##

- You control an enemy settlement or city when you control all adjacent land territories.
- The controlling player gets the victory points, resources, and harbors as if they had built it.
- The original player loses the victory points, resource gathering, and use of the harbor until it is recaptured.
- Note that all adjacent territories need to be controlled by the same player to have control of the settlement or city.
- You may maintain control of a settlement/city even if one enemy controls 2 of your home territories and another enemy player controls your 3rd home territory.

## Annexing Roads ##

- You annex an enemy road when you control all land territories that have that road as an edge.
- Captured roads prevent the transport of troops, unless the controlling player agrees to allow it through negotiation or trade.
- Hexes near annexed roads can be moved upon so long as there is no occupying army.

## Buying Armies ##

- To buy armies, during the building phase you declare a resource type.
    - You receive one army per resource of that type that you pay to the bank.
- You cannot change resource types until next turn.
    - For example, 4 armies would cost 4 ore, 4 wheat, 4 lumber, 4 brick, OR 4 sheep, but you may not mix and match.
- Each turn, you are limited to buying one army per victory point that you have.
    - For example, if you have 6 victory points, you may buy up to 6 armies that turn. (See Army unit type for full cost rules)
- Armies must be placed adjacent to villages or cities.

## Army Movement and Battle ##

- Armies are placed on hexes, they move, attack, and defend according to Risk battle rules.
    - Unlike Risk, troops must be situated in the same space as the people they are attacking unless otherwise specified (look at unit types).
    - Unlike Risk, there isn't a minimum of one troop staying behind.
- Armies may only move one space unless it is the cavalry unit (look at unit types).
- Armies may only move in territories (hexes) adjacent to roads/settlements/cities.
- Armies cannot move into through a hex that is occupied by an opponent.
    - They are forced to contest and sit until resolved or retreat back to previous hex.
- At the end of your turn, you may redeploy as many troops as you desire from one hex to any other hex, as long as there is a complete path of supply lines and trade routes connecting them.

## Army Unit Types ##

### Foot Soldier ###

- **Cost**: 1 resource
- **Description**: Normal foot soldier.
- **Movement**: Can only move one space per turn.
- **Attack Range**: Has a range of 1.

### Cavalry ###

- **Cost**: 2 resources
- **Description**: Troops on horses.
- **Movement**: Can move two spaces per turn.
- **Attack Range**: Has a range of 1.
- **Combat**: Has an attack bonus of 1 against foot soldiers but loses the defensive bonus given in Risk when attacked by foot soldiers.

### Cannon ###

- **Cost**: 3 resources
- **Description**: Giant cannon.
- **Movement**: Can only move one space per turn.
- **Attack Range**: Has a range of 2.
- **Combat**: Can barrage an army.
    - Roll a dice.
        - If 1-3 then it's a miss.
        - If 4-6 then it hits, and roll again.
            - This time, 1-2 = 1 kill, 3-4 = 2 kills, 5-6 = 3 kills.
    - Can only attack once per turn.
    - If enemy army enters into the same space as cannon and there is no other unit protecting it, the enemy automatically destroys the cannon.
    - Unit can move one space as long as there is a foot soldier occupying that space.
    - Cannot be used if the residing space is under attack. Enemies must be at least one space away.

## Elimination and Endgame ##

- Occasionally, players may be eliminated from the game, but this does not happen every game.
- If a player needs to leave the game, they are simply eliminated as if they were defeated in combat.
- However, if a player is eliminated when they do not have control over any settlements or cities then the eliminator takes control of all their buildings and roads.
    - All their troops are, however, eliminated from the game.
- If they leave, however, the eliminated player leaves all of their troops on the board, acting as defenders of the territories until they are defeated.
    - They do not get any bonuses for controlling territories and cannot be moved.
    - Any player may roll defense dice for the removed player.
- Any eliminated player's resource cards are returned to the resource bank.
- All of the eliminated player's development cards are shuffled back into the development card deck.
- First player to 10 or more points (on their turn) wins.
    - In the event that multiple players meet or exceed 10 points, the first player to still have 10 or more during their turn is declared the winner.

## Contributions ##

- Fork, add issues, add pull requests for typos, bugs, suggestions, etc!

modified from [/u/Kru5h](http://www.reddit.com/r/boardgames/comments/16kg3s/a_fun_game_my_friends_and_i_play_risk_of_catan/c7wtxkg)
