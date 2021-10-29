# NBDecoration
A free mode for Minecraft Pure Forge 1.12.2 servers that allows players to use dynamic Pixelmon objects as personal decorations (PokeChest, Shrines, Chalice, Chalise)

## Grab it
You can get the mod directly from my discord server in the dedicated channel.
https://discord.gg/u4hyCtybbr

## Permission
No permissions are required to use the plugin, however you will need the **nbdecoration.admin** permission to give the one decoration and have access to public mode.

*The public mode allows to place on the map a decoration that will be collectable by any player (which will become the owner of the decoration).*

## Usage
You just have to do a right click on the ground with a decoration to place it. You can collect it by right clicking on it. 
<br>**Only the player who placed the decoration can get it back (except for a public decoration)**<br><br>
*List of available decorations for your players with this mod, keep in mind that natural decoration are not considered as decoration by the mod.*<br>
![image](https://user-images.githubusercontent.com/30299182/139494906-9b7c9dbb-912a-4312-9c6e-97ee88e77fd8.png)
![image](https://user-images.githubusercontent.com/30299182/139495086-14e08547-88b2-4915-8748-670fdf21e500.png)


**Administrator**: *Administrator can break decoration in creative gamemode.*

## Commands

``/Decoration_Public``<br>
It is a toggle that you can enable / disable. Once activated decorations you will place, will be public, and players will be able to collected them.
<br><br>

``/Give_Decoration <Player> [Type] [Amount]``<br>
- ``<Player>``
- [Type] is optional, default is *PokeBall*
  - Ball
    - BallBeast
    - BallMaster
    - BallUltra
    - BallPoke
  - Shrine
    - ShrineZapdos
    - ShrineArticuno
    - ShrineMoltres
    - ShrineIlex
  - Rock
    - RockIce
    - RockMoss
  - AltarTimespace
  - ArcChalice
- [Amount] is optional, default is 1 (Integer)


<br>*Example:*<br>
``/give_decoration NicolasBrg AltarTimespace 10``<br>
![image](https://user-images.githubusercontent.com/30299182/139493554-df0540df-d6e4-41bc-9532-51badf57fb62.png)
