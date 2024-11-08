# awesome-tf2-devs
Curated list of development-related projects in the Team Fortress 2 space

If you want to contribue, easiest way is to click pencil icon on github to make a PR, we will most likely merge it.

## Related Lists
  * [CriticalFlaw/awesome-tf2](https://github.com/CriticalFlaw/awesome-tf2) - Tf2 comunities and events
  * [tf2 hud topic](https://github.com/topics/tf2-hud) - large collection of tf2 huds
  * [mastercoms hud list](https://comfig.app/huds/) - spiritual successor to huds.tf, more comprehensive than github topic
  

## Table of contents
- [Logs related](#Logs-related)
- [Demos related](#Demos-related)
- [Demo managers](#Demo-managers)
- [Discord bots](#Discord-bots)
- [Hosting](#Hosting)
- [Hud tools](#Hud-tools)
- [Format parsers](#Format-parsers)
- [Recording tools](#Recording-tools)

### Logs related
  * [Arie/logs_tf](https://github.com/Arie/logs_tf) - ruby - api wrapper for logs.tf
  * [TheBv/logstf-parser](https://github.com/TheBv/logstf-parser) - typescript - recreation of tf2 log parser in js, used for demoticks.tf
  * [tf2software/logstf](https://github.com/tf2-software-enthusiasts/the-library) - typescript - api wrapper and types for logs.tf

### Demos related
  * [demostf/parser](https://github.com/demostf/parser) - rust(+wasm) - parse tf2 demos, used for demos.tf
  * [demostf/edit](https://github.com/demostf/edit) - rust(+wasm) - edit tf2 demos, still WIP
  * [Square789/tf2_dem_py](https://github.com/Square789/tf2_dem_py) - C - C port of demostf/parser with python bindings

### Demo managers
  * [Narcha/DemoMan](https://github.com/Narcha/DemoMan) - typescript(electron) - desktop app to manage/tag tf2 demos 
  * [Square/789](https://github.com/Square789/Demomgr) - python(tkinter) - desktop app to manage/tag tf2 demos

### Discord bots
  * [payload-bot/payload-neo](https://github.com/payload-bot/payload-neo) - typescript - general comp tf2 bot, servicing 50k+ users. payload.tf
  * [TF2Autobot/tf2autobot](https://github.com/TF2Autobot/tf2autobot) - typescript - trading bot using backpack.tf and prices.tf

### Hosting
  * [spiretf](https://github.com/spiretf) - misc - tf2 server hosting related scripts/dockerfiles/tools/sourcespawn plugints
  * [spiretf/dispenser](https://github.com/spiretf/dispenser) - rust - Automatically spawn and destroy a tf2 servers in the cloud on a schedule
  * [vorboyvo/rcon](https://github.com/vorboyvo/rcon) - go - cli RCON utility
  * [rcontf/rcon](https://github.com/rcontf/rcon) - typescript - library for interacting with the rcon protocol
  * [rcontf/srcds-logs](https://github.com/rcontf/srcds-logs) - typescript - library for interacting with the srcds udp protocol
  
### Hud tools
  * [CriticalFlaw](https://github.com/CriticalFlaw/TF2HUD.Editor) - C# - tf2 hud editor and installer
  * [coolbros/hud-merger](https://github.com/cooolbros/hud-merger) - C# - merge components from different tf2 huds

### Format parsers
  * [icewind1991/sourcenav](https://github.com/icewind1991/sourcenav) - rust - parser for `.nav` files
  * [icewind1991/vmdl](https://github.com/icewind1991/vmdl) - rust - parser for `.mdl`, `.vtx` and `.vvd` files
  * [icewind1991/vbsp](https://github.com/icewind1991/vbsp) - rust - parser for `bsp` files
  * [roman901/vpk-rs](https://github.com/roman901/vpk-rs) - rust - parser for `vpk` files
  * [roman901/vtf-rs](https://github.com/roman901/vtf-rs) - rust - parser and encoder for `vtf` files
  * [Mark-Prime/vdm](https://github.com/Mark-Prime/vdm) - rust - parser and encoder for `vdm` files

### Recording tools
  * [quanticc/lawena-recording-tool](https://github.com/quanticc/lawena-recording-tool) - Java - Simple movie recording tool for Source Engine games
  * [advancedfx/advancedfx](https://github.com/advancedfx/advancedfx) - C++ - Advanced recording tools for Source Engine games
  * [Mark-Prime/Ryukbotv2](https://github.com/Mark-Prime/Ryukbotv2) - python - Automated tf2 clip recording/gathering

### Datasets

 * [parsed logs.tf logs](https://drops.tf/logs/dump/logs.sql.gz) - PostgreSQL dump - Logs from logs.tf in the json format returned by the API - Updated weekly
 * [normlaized logs.tf data](https://drops.tf/logs/dump/logs.sql.gz) - PostgreSQL dump - Data from logs.tf in normalized form for easier analysis - Updated weekly
 * [raw logs.tf logs](https://drops.tf/logs/archive/) - [dwarfs](https://github.com/mhx/dwarfs) archive - Raw log files from the first 3 million logs.tf logs (newer logs can be found [here](https://drops.tf/logs/logs/3000000/))
 * [drops.tf metadata](https://freezer.demos.tf/database/demostf.sql.gz) - PostgreSQL dump - Metadata from all demos.tf uploads - Updated weekly
