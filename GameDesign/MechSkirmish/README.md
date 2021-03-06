# Mech Skirmish Game
For this game I would like to make a skirmish type game with mechs. This was
inspired by the game GKR Heavy hitters, which is a cool looking game but has a
bunch of mechanics that I think are dumb. It does have some really good ideas
though. I would like to borrow a lot from the Star Wars X-Wing skirmish game,
but played on a hex board. I would also like to take from Heavy Hitters the
deck and damage system. So you build a deck of cards at the begining that you
use as your hand and also when you take damage you discard cards. When you run
out of cards you are destroyed.

## Basics
Each player will choose a mech to play. Once you choose that mech you are given
the deck of cards associated with that mech. You then choose cards to make up
your deck. Each player will be limited in the number of cards they may choose (
Maybe all the same, say 25, or maybe mech dependent). The cards also make up
your hit points and represent systems breaking when you take damage. This would
be accomplished by you discarding cards into a 'damage' pile when you take
damage. One of the
biggest choices in building the deck will be which weapons you take. There will
be a main gun and also several secondary weapons like missiles. Choosing which
weapons to take will change how your mech plays on the battle field. I am thinking
right now that you might have the choice between two main guns and when you choose
one you must take all cards associated with that gun. So there will be several
different things you can do with that gun like 'Aimed shot' which is slow, but
has higher chance of hitting, or 'hipshot' which is faster but less likely to hit.
Things like that. Some guns could also have crazier things too, like charge it up
and it can shoot through cover. Maybe that could be something that has only 1 card
where as more common 'just shoot' kind of attacks will have 2 or 3.

All play will take place on a hex board and there will be buildings or other
terrain pieces that can count as cover. Other pieces on the board might be
objectives or scenario specific things that you have to get to or move around.

Mechs will also have smaller mechs/vehicles that they can deploy or that they
start with to help out. These will be things like a repair mech that can help you
get cards from your damage pile back into your hand. Maybe have ground troops too.
Units that arent in a mech at all.

## Game Ideas Wishlist
Some general ideas or mechanics that I would really like to figure out how to
include.
 - Secret movement selection:
   * X-wing uses dials to select your movement and eveyone picks in secret all
   at once. The dials are then flipped and movement proceeds based on the skill
   of the pilot. For this game I would like to include the secret movement to
   get that feel of dog fighting that x-wing has.
   * I dont know if dials will work for this since it will be card based. The
   other option is making the movement card based. Each player could play a
   card in secret then execute the move based on the speed of the movement
   printed on the card. I am a little bit worried that this will make movement
   too limited since you will only be able to play what is in your hand. One
   big positive of this is that each mech could feel really different since
   they will all have their own unique deck to build from.
   * Another option is that you could select your movement in secret from a
   dial or something like that where there are only basic moves. e.g. 2 forward,
   2 forward and turn around, etc... But where the cards come into play are with
   special maneuvers, like sprint 4 spaces, or move 1 forward then hook sideways.
   These special maneuvers could then provide some combat bonuses or negatives.
   For example if you use the sprint forward card, you have +1 defense but -1
   attack or something like that. The biggest problem is moving in secret. If you
   are placing a card down it is pretty obvious that you are doing a special move.
   Maybe there could be a spot on the dial for play card, so you select it on
   the dial, then once players flip their dials to reveal, you can then play a
   card if you selected that movement option.
   * Something else that might work if cards are used for movement is that instead
   of separating the movement and attack phases, you combine them. Maybe require
   that the players both play two facedown cards. These cards could be any combination
   of movement and attack. This could be really interesting if you have some attacks
   that require you to target a specific space. Like firing a missile volley that
   deals damage within 1 range of a specific hex. Then if this is a slow attack,
   there is a chance that the enemy mech might move out of the attack zone before
   the missiles actually land. This might be kind of a cool way to simulate the
   hectic "dog fighting" type combat with mechs dodging and such. Then you could
   also have attack cards that cannot be played with a movement card or that get
   negatives if they are played with a movement card. Im still a little worried
   about this limiting movement too much. Like you dont have any moves in your
   hand, or you dont want to move but only have movements.
   * All secret selection could be done behind a screen. That way if you dont
   play anything the other players cant tell. So once everyone says they are done
   making their selections, all players just lift their screen then start to
   resolve moves and attacks.


 - Power Consumption:
   * I would also like to add in power consumption on a per tern basis. So,
   you would have X number of power points to use per tern and different things
   cost different amounts of power. You can use more power than you have available
   per turn but it causes damage to your mech (like you are running into the redline).
   Every card can have a power number on it that you mush spend to play that card.
   Then depending on how the balancing works out you could make the standard movements
   use some fixed amount of power.

 - Attacking and Defending:
   * I think I want to use a system like X-wing uses where you roll dice and just
   count up the number of hits. I think the easiest thing would be to use D6
   and have a number that you have to make to hit (5+ for example), then things
   can either increase the number of dice you roll (higher damage is more dice)
   and adjust the chances you have to hit (a lower number needed, 4+). Then the
   defender rolls dice and successful defend results cancel out hits. The same
   ideas apply to number of dice and the number needed to defend. In addition
   to attack cards you could put in defense cards too. For instance one mech has
   a short term shield that it can use, so when you play the shield card you
   now have really high defense for that combat round. I think how the combat
   round could progress is that both players play cards face down, then reveal
   at the same time similar to movement. Then attacks are resolved in order of
   speed.
   * another option is to use special dice that just have hits and blanks on them.
   for defending it could be similar, with dodges and blanks or whatever.

 - Cover:
   * I like how Heavy Hitters does cover on the hexes. If the shortest path between
   you and your target doesnt go through anything than you have no cover. If there
   are two shortest paths and one of them goes through something then you have
   partial cover. If there is only one shortest path and it goes through something
   then you have full cover (and maybe cant be hit at all).

## Early Test Versions:
To start out I think I am going to just print off a deck of cards to do some testing with.

### Version 0.0.1
This will be the version where all movement is done through cards. Every turn
all players will select up to two cards and place them behind their screen. Once
all players have finished selecting cards, all players will lift their screens
and begin to resolve actions in the order of fastest(lowest number) to slowest(highest number).

This version will not use the auxiliary units yet and will not have mech power
either.

Basic rules and a growing list of all cards to be used can be found in the
[Rules version 0.0.1 file](./rules-00-00-01.md)
