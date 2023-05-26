


# [FOF] Gun Game Gamemode

<p align="center">  <img src="https://connorrichlen.me/images/fof_lg.png"> <b>Gun Game Gamemode</b>   </p>


  

This plugin adds a Gun Game gamemode. It is an updated version of [CrimsonTautology's old release](https://github.com/CrimsonTautology/sm-gungame-fof). Has a couple fun commands, also.

## Requirements
* [SourceMod](https://www.sourcemod.net/) 1.10 or later

## Installation
Make sure your server has SourceMod installed.  See [Installing SourceMod](https://wiki.alliedmods.net/Installing_SourceMod).  If you are new to managing SourceMod on a server be sure to read the '[Installing Plugins](https://wiki.alliedmods.net/Managing_your_sourcemod_installation#Installing_Plugins)' section from the official SourceMod Wiki.

Download the latest [release](https://github.com/connorrichlen/fof_gungame/releases/latest) and copy the contents of `addons` to your server's `addons` directory. 

SteamWorks extension is also required for the server to run correctly. Get the latest build for either windows or linux here: https://users.alliedmods.net/~kyles/builds/SteamWorks/. Again, copy the contents of `addons` to your servers `addons` directory. 

It is recommended to restart your server after installing.

To confirm the plugin is installed correctly, on your server's console type:
```
sm plugins list
```

 <hr />
 
### Player Commands

| Command | Accepts | Values | SM Admin Flag | Description |
| --- | --- | --- | --- | --- |
| `fof_gungame_restart` | None | None | Generic | Force restart the round |
| `fof_gungame_reload_cfg` | None | None | Config | Force a reload of the configuration file |
| `fof_gungame_scores` | None | None | Root | (debug) List player score values to console |
| `sm_stopmusic` | None | None | Everyone | Stops music from `fof_gungame_music` |


### Console Variables

| Command | Accepts | Values | Description |
| --- | --- | --- | --- |
| `fof_gungame_enabled` | boolean | 0-1 | Whether or not Gun Game is enabled |
| `fof_gungame_config` | string | file path | Location of the Gun Game configuration file |
| `fof_gungame_fists` | boolean | 0-1 | Whether or not to allow fists in game.  Killing someone with fists will reduce their level |
| `fof_gungame_whiskeyjug` | boolean | 0-1 | Toggles whiskeyjug use |
| `fof_gungame_whiskey` | boolean | 0-1 | Toggles spawning of MAP WHISKEY |
| `fof_gungame_heal` | float | 0-100 | Amount of health player recieves when ranking up |
| `fof_gungame_equip_delay` | float | 0-999 | (deprecated) Seconds before giving new equipment on spawn |
| `fof_gungame_drunkness` | float | 0-999 | (deprecated) Amount of "drunkness" player recieves when ranking up |
| `fof_gungame_logfile` | string | file path | (deprecated) Location of the Gun Game log file |
| `fof_gungame_suicides` | boolean | 0-1 | Toggles if suicide levels down |

### Useful Things

| Command | Accepts | Values | Description |
| --- | --- | --- | --- |
| `fof_sv_weaponmenu` | boolean | 0-1 | Enables showing the weapon menu |
    
 <hr />
