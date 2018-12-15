# smash_lib
A library used for detecting smashed entities in MC 1.13+

Includes 2 action types:
1. smashed by anvil - this works on all entities
2. smashed by piston facing downwards - this works only on items

Also it includes 2 example recipes:
1. Dropping an anvil on top of an iron block will result in 5 heavy weighted pressureplates
2. Smashing an iron block with a piston will result in 9 iron ingots

To use this:

Anvil Tag => smashed_anvil

Piston Tag => smashed_piston

Smashed entities get the tags for one tick.



Made with mcscript by stevertus (stevertus.com)
