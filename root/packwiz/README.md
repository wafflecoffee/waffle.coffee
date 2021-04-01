# waffle's Mods

***Featuring the [Empire Minecraft Utilities](https://modrinth.com/mod/emcutils) mod, made by [GreenMeanie](https://u.emc.gs/GreenMeanie) with help from yours truly!***

Don't want to update your Fabric mods? Let me do it for you! I set up this here modpack that downloads the latest of a predefined set of mods. This is an easier way to download one thing to get all of the mods included instead of having to download 40+ separate mods.

Feel free to remove or add any (compatible, [approved](https://mods.emc.gs)) mods!

**Please read the [Conditionally Approved Mods](https://wiki.emc.gs/conditionally-approved-mods) page before using the Command Macros, Litematica, and Xaero's Minimap/World Map mods.**

*Note: Blur is known to be stupidly laggy. Removing this will give a significant performance boost for some.*

## Versions

There are two versions of the pack.  
* **Sodium** *(recommended)*: This pack is for those who want a few more mods. This is the pack I use personally. It includes some optional tools that very few people would actually utilise, such as Critical Orientation or WorldEditCUI, and it will prompt you at installation whether you wish to install these optional mods or not. It includes all of the performance-enhancing mods.  
* **OptiFine**: This pack is the same as the Sodium pack, but with OptiFine instead of some of the performance enhancing mods. This should only be used if you wish to use shaders.

## Installation
### MultiMC

1. Download the Packwiz Installer Bootstrap from [here](https://github.com/comp500/packwiz-installer-bootstrap/releases/download/v0.0.3/packwiz-installer-bootstrap.jar), and put it into your Minecraft folder.  
2. Under "Edit Instance", go to "Settings" and then "Custom Commands", and add the following pre-launch command: `"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://waffle.coffee/packwiz/{DESIRED PACK}/pack.toml`  
    * `{DESIRED PACK}` should be changed to `sodium` or `optifine`; whichever one you want.  
3. Use the Export Instance function to export the pack as a `.zip` file.  
4. To install the pack, you need to add it with "Add Instance" and "Import from zip".

Credit for the instructions go to comp500, the creator of Packwiz, [here](https://github.com/comp500/packwiz#packwiz-installer-for-pack-installation).

### Default Launcher
#### Windows
1. Download the Packwiz Installer Bootstrap from [here](https://github.com/comp500/packwiz-installer-bootstrap/releases/download/v0.0.3/packwiz-installer-bootstrap.jar), and put it into your Minecraft folder; the base of it, not into the \mods folder.  
    * If you don't know how to navigate here, open the run box with Win + R, and type `%appdata%\.minecraft`.  
2. Open the Command Prompt with Win + R and `cmd`. From there, run the following commands:  
3. `cd %appdata%\.minecraft`  
4. `java -jar packwiz-installer-bootstrap.jar https://waffle.coffee/packwiz/{DESIRED PACK}/pack.toml`  
    * `{DESIRED PACK}` should be changed to `sodium` or `optifine`; whichever one you want.  
5. You can close out of Command Prompt now, and delete the Packwiz Bootstrap Installer.

#### Unix (Linux, Mac)
Run the following commands (you can also append `&&` between them):  
1. `cd ~/.minecraft`  
2. `wget https://github.com/comp500/packwiz-installer-bootstrap/releases/download/v0.0.3/packwiz-installer-bootstrap.jar`  
3. `java -jar packwiz-installer-bootstrap.jar https://waffle.coffee/packwiz/{DESIRED PACK}/pack.toml`  
    * `{DESIRED PACK}` should be changed to `sodium` or `optifine`; whichever one you want.  
    * You can pass `-g` if you want all of the optional mods.
4. `rm -f packwiz-installer-bootstrap.jar`  

Change the directory from `~/.minecraft` if you use a different directory, e.g., if you're on Mac, or use Snap or Flatpak.

## Mod List

**Legend:**  
* *Yes* - The mod is always downloaded.  
* *Optional* - The mod is only downloaded if you check the box to, or if you pass the `-g` argument.  
* *No* - This mod conflicts with another included in the pack, and therefore is not included in that pack.

| Mod Name                                                                                                           | Sodium   | OptiFine | Comment                                                                                                       |
|--------------------------------------------------------------------------------------------------------------------|----------|----------|---------------------------------------------------------------------------------------------------------------|
| [AntiGhost](https://modrinth.com/mod/Jw3Wx1KR)                                                                     | Optional | Optional |                                                                                                               |
| [Architectury API](https://www.curseforge.com/minecraft/mc-mods/architectury-fabric)                               | Yes      | Yes      | Dependency of Light Overlay                                                                                   |
| [Better Enchanted Books](https://www.curseforge.com/minecraft/mc-mods/better-enchanted-books)                      | Optional | Optional |                                                                                                               |
| [Blur](https://modrinth.com/mod/NK39zBp2)                                                                          | Yes      | Yes      |                                                                                                               |
| [Clear Skies](https://www.curseforge.com/minecraft/mc-mods/clear-skies)                                            | Optional | Optional |                                                                                                               |
| [ClickThrough](https://modrinth.com/mod/Z5b0cAlD)                                                                  | Yes      | Yes      |                                                                                                               |
| [Cloth Config](https://www.curseforge.com/minecraft/mc-mods/cloth-config)                                          | Yes      | Yes      | Dependency of multiple other mods                                                                             |
| [Command Macros](https://www.curseforge.com/minecraft/mc-mods/command-macros)                                      | Optional | Optional | Conditionally Approved                                                                                        |
| [Critical Flight Details](https://www.curseforge.com/minecraft/mc-mods/critical-flight-details)                    | Optional | Optional |                                                                                                               |
| [Critical Orientation](https://www.curseforge.com/minecraft/mc-mods/critical-orientation)                          | Optional | Optional |                                                                                                               |
| [Dark Loading Screen](https://www.curseforge.com/minecraft/mc-mods/dark-loading-screen)                            | Yes      | No       |                                                                                                               |
| [Durability Viewer](https://modrinth.com/mod/LTM1f0yY)                                                             | Yes      | Yes      |                                                                                                               |
| [Dynamic FPS](https://modrinth.com/mod/LQ3K71Q1)                                                                   | Yes      | No       | Fabric port of the approved Forge mod [FPS Reducer](https://www.curseforge.com/minecraft/mc-mods/fps-reducer) |
| [EasierCrafting](https://modrinth.com/mod/UylF21yz)                                                                | Yes      | Yes      |                                                                                                               |
| [Empire Minecraft Utilities](https://modrinth.com/mod/QYTT62S0)                                                    | Yes      | Yes      |                                                                                                               |
| [Fabric API](https://modrinth.com/mod/P7dR8mSH)                                                                    | Yes      | Yes      |                                                                                                               |
| [Fabrishot](https://modrinth.com/mod/3qsfQtE9)                                                                     | Yes      | No       |                                                                                                               |
| [Flight Helper](https://modrinth.com/mod/1yyNJogn)                                                                 | Yes      | Yes      |                                                                                                               |
| [HWYLA](https://www.curseforge.com/minecraft/mc-mods/hwyla)                                                        | Yes      | Yes      |                                                                                                               |
| [Hydrogen](https://modrinth.com/mod/AZomiSrC)                                                                      | Yes      | Yes      |                                                                                                               |
| [Inventory Profiles](https://www.curseforge.com/minecraft/mc-mods/inventory-profiles)                              | Yes      | Yes      |                                                                                                               |
| [Item Scroller](https://www.curseforge.com/minecraft/mc-mods/item-scroller)                                        | Yes      | Yes      |                                                                                                               |
| [Krypton](https://modrinth.com/mod/fQEb0iXm)                                                                       | Yes      | Yes      |                                                                                                               |
| [LambDynamicLights](https://modrinth.com/mod/yBW8D80W)                                                             | Yes      | No       |                                                                                                               |
| [Light Overlay](https://www.curseforge.com/minecraft/mc-mods/light-overlay)                                        | Optional | Optional |                                                                                                               |
| [Litematica](https://www.curseforge.com/minecraft/mc-mods/litematica)                                              | Yes      | Yes      | Conditionally Approved                                                                                        |
| [Lithium](https://modrinth.com/mod/gvQqBUqZ)                                                                       | Yes      | Yes      |                                                                                                               |
| [Low Fire](https://modrinth.com/mod/Gou1gmGj)                                                                      | Optional | Optional | Conditionally Approved                                                                                        |
| [MaLiLib](https://www.curseforge.com/minecraft/mc-mods/malilib)                                                    | Yes      | Yes      | Dependency of multiple other mods                                                                             |
| [MiniHUD](https://www.curseforge.com/minecraft/mc-mods/minihud)                                                    | Yes      | Yes      |                                                                                                               |
| [Mod Menu](https://modrinth.com/mod/mOgUt4GM)                                                                      | Yes      | Yes      |                                                                                                               |
| [Mod Updater](https://www.curseforge.com/minecraft/mc-mods/modupdater)                                             | Yes      | Yes      | Dependency of Giselbaer's mods                                                                                |
| [No More Useless Keys](https://modrinth.com/mod/YCcdA1Lp)                                                          | Optional | Optional |                                                                                                               |
| [No Strip](https://modrinth.com/mod/3f1BdVqy)                                                                      | Optional | Optional |                                                                                                               |
| [NoFog](https://www.curseforge.com/minecraft/mc-mods/nofog)                                                        | Optional | Optional | Conditionally Approved                                                                                        |
| [Not Enough Crashes](https://www.curseforge.com/minecraft/mc-mods/not-enough-crashes)                              | Yes      | Yes      |                                                                                                               |
| [Ok Zoomer](https://modrinth.com/mod/aXf2OSFU)                                                                     | Yes      | No       |                                                                                                               |
| [OptiFabric](https://www.curseforge.com/minecraft/mc-mods/optifabric) & [OptiFine](https://optifine.net/downloads) | No       | Yes      |                                                                                                               |
| [Phosphor](https://modrinth.com/mod/hEOCdOgW)                                                                      | Yes      | Yes      |                                                                                                               |
| [ReAuth](https://www.curseforge.com/minecraft/mc-mods/reauth-fabric)                                               | Optional | Optional |                                                                                                               |
| [Shulker Box Tooltip](https://www.curseforge.com/minecraft/mc-mods/shulkerboxtooltip)                              | Yes      | Yes      |                                                                                                               |
| [Smooth Scrolling Everywhere](https://www.curseforge.com/minecraft/mc-mods/smooth-scrolling-everywhere-fabric/)    | Optional | Optional |                                                                                                               |
| [Smooth Boot](https://modrinth.com/mod/FWumhS4T)                                                                   | Yes      | No       |                                                                                                               |
| [Sodium](https://modrinth.com/mod/AANobbMI)                                                                        | Yes      | No       |                                                                                                               |
| [ToroHealth Damage Indicators](https://www.curseforge.com/minecraft/mc-mods/torohealth-damage-indicators)          | Yes      | Yes      |                                                                                                               |
| [WorldEdit](https://www.curseforge.com/minecraft/mc-mods/worldedit)                                                | Optional | Optional | Incompatible Mod (intended for singleplayer use)                                                              |
| [WorldEditCUI](https://github.com/mikroskeem/WorldEditCUI/)                                                        | Optional | Optional |                                                                                                               |
| [Xaero's Minimap](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap)                                     | Yes      | Yes      | Conditionally Approved                                                                                        |
| [Xaero's World Map](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map)                                 | Yes      | Yes      | Conditionally Approved                                                                                        |