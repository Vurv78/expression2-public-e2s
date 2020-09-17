# Hook Library in E2
Isolate runOn* calls to single functions!
## Docs Created with e2tinytokenizer
More @https://github.com/Vurv78/expression2-public-e2s

## List of hooks added

addHook("tick","tickClk","runOnTick")

addHook("chat","chatClk","runOnChat")

addHook("file","fileClk","runOnFile")

addHook("death","deathClk","runOnDeath")

addHook("spawn","spawnClk","runOnSpawn")

addHook("playerconnect","playerConnectClk","runOnPlayerConnect")

addHook("playerdisconnect","playerDisconnectClk","runOnPlayerDisconnect")

addHook("last","last","runOnLast")

addHook("list","fileListClk","runOnList")

addHook("http","httpClk","runOnHTTP")

## Functions that return **void**

### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = hookRemove(Hook ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-String.png), ID ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-String.png))
 Removes a hook so it isn't called or saved anymore.
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = hookAdd(Hook ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-String.png), ID ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-String.png), Func ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-String.png))
 Whenever hook [hook] runs, the function [func] given will be called and only that function. It behaves like runOn* except only runs that function like how lua works.
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = addHook(HookName ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-String.png), CB ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-String.png), Call ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-String.png))
 Creates a hook, used internally to define what hooks can be called. Don't use this unless you know what you're doing.
