# Game overview

This game is going to be (once finished) about information.

So imagine a unit sortied somewhere.
To tell that unit to change direction, instead of them changing when you say
so, you have to send a messenger to tell them to move.
The thing is, if the messenger is stopped, the unit will not change directions.
But your opponents will obey the same rules as you do.
So by intercepting enemy messenger, some enemy unit might never get their orders.
Just to be sure, but no, you won't have to always send the messengers one by one
for each order you give, you will be able to give a sequence of orders, and even
reactions to events (ex: if you see an enemy, retreat).

I don't know yet how I'll do different kinds of units, but probably not that deep.
The game's strategy should come from the handling of information and how you
can use your units.
(although, the more I think about it, the more I feel like they might become
more interesting when I get to it)
One of the goals is that no set of unit in any situation is completely unbeatable.

Something else that will be added, is the map information.
It will mean that your map will only be updated once some unit comes back to
you with the info (info: terrain, enemy position, resources, ...).
Which means you won't know for sure where your units are without regular contact.
(it wouldn't be fun if you knew your messengers didn't get to a unit, now, would
it ?)

Something that, I'm really really not sure will be added, is spies to get enemy
info and corrupt info.
I don't think I'll add them, because as I want to avoid unfair situations, there
should be a way to counter them.
But that's the thing, I have absolutely no idea how I'd do that (skill issue).
It might fit with the mechanics, but I don't think it'd fit with the gameplay.

To help with the lack of info, the map will allow you to place custom info.
Once implemented, it will allow the player to place indicators and information
on their map (things like, the path a unit is supposed to take, when a messenger
is supposed to come back, ...)
and probably other things. This will depend a LOT on what will be implemented
(and probably won't be there at the start).

Also, something else, even if you don't have information, that doesn't mean it's
random.
One of my goals, is to take out the randomness as much as possible.
Not just as in random events, but as in, someone who is very good at the game
should almost (if not) always win against someone who's not.

Scope creep ? What's that ? Never heard of it.

## Stuff

Exams are coming up, so I shouldn't be working too much on it for now.
If I do and you see it, please, tell me to stop.

Also, I starting coding a game loop, a mini component system and all, until i
remembered my goal isn't to make a game engine (or at least, not yet), but to do
a game.
So I'm starting with bevy, this time.

## Current tasks

This is a list of the task i should be working on before starting something else.
(and it will be continuously updated as i work on this project)

- [ ] Game Logic
