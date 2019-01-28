# marball_modness

### tl;dr

Marball Modness is a mod designed to allow players to construct super expensive but explicitly TPS friendly post-endgame factories with fun client-side visualisations.

### huh?

First - we need to get this out of the way up front.

Do any of these sound like the kind of thing you say about other mods?
- "*Eugh!* That item is so _OP_! It totally ruins the game!"
- "*Eugh!* I think the first few tiers of that mod are ok. But that expensive _magic-in-a-box_ machine that you had to complete the entire rest of the pack to craft that doesn't force you to fill another three chunks full of ticking TileEntites totally ruins the game!"
- "*Eugh!* What do you mean you don't have to know how DFS/BFS/Dijkstra's algorithm works to be able to use that mod? That totally ruins the game!"

If so, then this may not be the mod for you. :)

### So who is this mod for then?

This mod is explicitly intended to reduce the TPS footprint of post-endgame players on multi-player servers running kitchen-sink tech modpacks with exponential economies.

While the ultimate machines in M.M. *are* meant to be 'stupidly expensive' to ensure players have already completed a ton of progress before they get to the really OP stuff, they are *not* intended to be beyond stupidly expensive. The entire raison d'être for this mod is to allow endgame players to _reduce_ their TPS footprint on multiplayer servers by replacing huge setups with a (pretty) magic box, not to require them to build another chunkfull of TileEntities.


# FAQ

### So, do you really love marble runs or something?

Not really. Well - I mean - of course I do. Who doesn't love watching those things? Recreational physics is beautiful!

But the truth is that I've wanted to write a super-TPS-friendly post-endgame mod for years now, ever since I first saw a multi-player server slowly tick to death under the load of a mere 3-4 endgame players. But seeing all the trash-talking people seem determined to spout about endgame content made it clear that any attempt at such a mod would fail unless it had both (a) some kind of problem-solving mechanic; and ideally (b) an entertaining client-side rendering option that would not require constant network updates.

And then one day while watching a marble run video the idea finally clicked.

### Your mod is still O.P.

This mod is intended for kitchen-sink tech modpacks. The kind of pack where you see people building literal rows of pulverizers and furnaces processing the output of an energy quarry that spits out ores every tick, using hundreds or thousands of blocks worth of cables and networks pumping items in and out of chests and buffers all over the place!

Once a player has crossed the resources threshold into the endgame of a kitchen-sink tech pack nothing in the game stops them from building massive factories full of TileEntities. And thus begins the inevitable arguments between the players and the Admins about exactly how much TPS each individual player is 'entitled' to consume.

An ultimate M.M. isn't meant to be compared to a single TileEntity from other mods. It's meant to replace _dozens of them_ with an implementation explicitly designed to run as efficiently as possible on the server.

### _argh_! Could you please fix your spelling mistakes?

Sorry, I deliberately chose the name of the mod to be sufficiently unique to be searchable (both on the web and in NEI/JEI) as there are so many other mods that have a ton of "marble" items now. Also, I like bad puns. >:)


# Licenses

Unless otherwise specified any files that were newly created for this reposiroty are licensed as per the terms of the [Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0) license](https://creativecommons.org/licenses/by-nd/4.0/).

Explicitly designated json configuration files and the internationalisation translation files are an exception to the above, and licensed as per the terms of the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) license](https://creativecommons.org/licenses/by-sa/4.0/).

*In simple terms, the intention of these licenses are as follows:*
- this is not currently any kind of "open source" mod
- you are not permitted to distribute any changes you might make to any of the source and/or compiled files without my permission

*however:*
- I will try to make as many settings as possible configurable via the external json files to allow people/modpacks to experiment/tune the difficulty/progression to their preferences
- as a hobby endeavour (and to avoid being pranked) I will likely only accept translations from contributers with an existing record of reliable translation contributions, so non-EN translation files will need to be sourced from somewhere else

Due to the very specific design goals of this mod there won't be a custom API in the way many other mods do. But if this mod ever does get picked up I can re-visit that decision and/or add functional blocks to perform tasks for other mods.
