
# BlackMUDlet

BlackMUDlet is a [BlackMUD](www.blackmud.com) client package for the [Mudlet](https://www.mudlet.org/) MUD client.

<p align="center">
  <img width="600" src="https://raw.githubusercontent.com/blackmud-dev/bm-mudlet/main/screenshot/blackmudlet.png">
</p>

BlackMUDlet consists of two primary components:

1. [BlackMUDlet UI](https://github.com/blackmud-dev/bm-mudlet/wiki/Home/_edit#blackmudlet-ui): A User Interface for displaying game-related information on a series of informational panels.
1. [BlackMUDlet Mapper](https://github.com/blackmud-dev/bm-mudlet/wiki/Home/_edit#blackmudlet-mapper): A mapping script to enable mapping using Mudlet's built-in mapping tools.

Several methods for interacting with the UI, game, and map data are also included within the package.

BlackMUDlet is powered by the Generic MUD Communication Protocol (GMCP), a JSON-based message format containing information sent directly from BlackMUD to the client outside of the usual game connection. This enables a reliable stream of game-related information without any complicated parsing of MUD output. The goal of BlackMUDlet is to integrate this stream of information into the Mudlet client via a basic UI such that any Mudlet user can benefit from it. BlackMUDlet explicitly avoids using this information to automate player actions.

Visit the [Wiki](https://github.com/blackmud-dev/bm-mudlet/wiki) for more information.
