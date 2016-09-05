# SAPDFR-Sandy

Just several spawn points around the Sandy Shores Police Department with the male sheriff model. Once I learn more about how to use FiveReborn, may contain other things.

## Installation

Clone this repository into your `resources` folder and add `sapdfr-sandy` to your `citmp-server.yml` file.

Just make sure `__resource.lua` and `map.lua` are *not* in a subfolder.

An example `citmp-server.yml`:

```
ListenPort: 30120

PreParseResources:
    - mapmanager

AutoStartResources:
    - fivem
    - chat
    - spawnmanager
    - sapdfr-sandy
    - baseevents

RconPassword: something

Hostname: SAPDFR Sandy Shores

Game: GTA5

PlatformServer: updater.fivereborn.com

ScriptDebug: true

DebugLog: true

Announce: true

DisableAuth: true # Keep this off to avoid terminal bullshit
DisableScriptHook: false
```
