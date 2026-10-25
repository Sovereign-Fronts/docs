---
title: Creating a Server
permalink: /setup/server-creation/
---

In order to create a server you can follow the instructions directly available in the official repository found [here]() or follow along with the more detailed instructions below.

## Things to consider

- **Server uptime:** Sovereign Fronts is a game that requires the server to be constantly online for progression to happen as expected. This means that a dedicated server or host is typically preferred over a personal computer. However when playing with friends the latter might be more economical, while the former is generally a better choice when hosting a large-scale server.

- **exe or archive:** A cinnamon server can be run as a folder or as an executable. Using the executable is generally preferred for small servers/small communities or playing with friends as it is easier to manage, requiring no other installs to run. However for bigger servers we heavily recommend using the archive format as it is more secure and allows you to edit the source-code directly. Unlike the executable running it as-is also means you can make use of the Deno permission system, making it a much safer and reliable way of hosting.

- **updating:** Generally it is not recommended to update your server unless 