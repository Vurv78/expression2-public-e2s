# SpawnSent Library in E2. 
 This library spawns scripted entities like npcs and guns by using concmd and nexuscore's teleport function.
 You can replace the function with another external teleport function, but this needs atleast one.
## Docs Created with e2tinytokenizer
More @https://github.com/Vurv78/expression2-public-e2s

## Functions that return **void**

### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = spawnSent(Class ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-String.png), Pos ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Vector.png), Ang ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Angle.png), Frozen ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), Timeout ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), Type ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png))
 Spawns a scripted entity.\n Takes [Class] [Pos] [Ang] [Frozen] and a number for how long to wait for the prop to exist. \n The last argument is a number to define the type of sent, which should be 1 for a regular sent, 2 for an npc, 3 for a vehicle, 4 for a SWEP/weapon and 5 for props, but also works with stuff like the mattress prop, keeping it a ragdoll.
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = cleanupSents()
 Cleans up all of the sents currently kept track of with the library, this will not work for props that were not detected and didn't get teleported.
