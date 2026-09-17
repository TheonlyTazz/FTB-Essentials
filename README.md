# FTB Essentials

FTB Essentials adds configurable utility commands for Minecraft servers. It is
implemented as a shared Architectury project with Fabric and NeoForge platform
modules.

## Features

- Teleportation utilities, including homes, warps, spawn, back, random
  teleportation, teleport requests, and administrator teleport tools
- Server administration and moderation commands, including healing, feeding,
  flight, invulnerability, inventory viewing, kits, muting, and offline-player
  teleportation
- Player utilities such as nicknames, nearby-player and leaderboard views,
  recording/streaming status, a trash can, and access to utility inventories
- Configurable command availability, permissions, warmups, cooldowns, limits,
  and teleportation dimension filters
- Optional integration with FTB Ranks and LuckPerms

## Compatibility and prerequisites

The current project targets Minecraft **1.21.1** and Java **21**. The enabled
platforms are:

- Fabric, with Fabric Loader, Fabric API, Architectury API, and FTB Library
- NeoForge, with NeoForge, Architectury API, and FTB Library

FTB Ranks is optional. LuckPerms is an optional server-side integration on
NeoForge and is available as a compile-only integration for Fabric.

## Installation

Build the platform jar that matches the server, or obtain a release through
your normal mod distribution channel. Place the resulting
`ftb-essentials-<platform>.jar` in the server's `mods` directory alongside its
required dependencies.

After the first launch, configure the mod in
`config/ftbessentials.snbt`. Modpack authors can provide server defaults in
`defaultconfigs/ftbessentials-server.snbt`.

## Development

Clone the repository and build all enabled platform modules with the Gradle
wrapper:

```text
gradlew.bat build
```

On Unix-like systems, use `./gradlew build`. Platform artifacts are written to
the corresponding platform module's `build/libs` directory.

## Links

- [Source code](https://github.com/FTBTeam/FTB-Essentials)
- [Issue tracker and support](https://go.ftb.team/support-mod-issues)

FTB Essentials is released under **All Rights Reserved**.
