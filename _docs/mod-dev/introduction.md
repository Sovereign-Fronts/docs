---
title: Server Flavors
permalink: /mod-dev/introduction/
---

Mods on Cinnamon are primarily written in JavaScript, the language commonly associated with the web. This means that you will need to have at least some basic knowledge on JavaScript or coding itself.

> [!NOTE]
> If you do not know any JavaScript you can use this [free source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide) to learn the basics.


## Mods & plugins
Sovereign Fronts by default distinguishes between two types of mods:
- Plugins run once on server initialization as part of the server process itself. They aren't tied to any specific game itself. Such mods for example could be server-wide ip ban mods, admin tools game administration and more. These live in the `plugins` folder.
- Mods run on both the client and server per game instance. They can be enabled or disabled when a player creates a match, and usually revolve around adding, removing or changing game mechanics. For example adding new units, events, mechanics or rules. These live in the mod folder. Currently in cinnamon mods on the server dispose of the **Deno Runtime** api, although it is recommended to refrain from using it when possible.

> [!NOTE]
> This documentation is specifically catered to the **cinnamon** modding platform. It may not apply to other modding platforms.