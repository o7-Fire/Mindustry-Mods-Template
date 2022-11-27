# Mindustry-Mods-Template
V7\
Note: automatically use d8 and make dexed jar if detected

### How to get indexed by mods browser
![](https://cdn.discordapp.com/attachments/713346278003572777/821210982449807380/unknown.png)

### How to build and run

- `gradle run` install the mod and run it in just single command

### How to make jar for android

- install Android SDK ???
- add to ANDROID_HOME environment
- gradle makeJar
- Dex = Dex only no class
- Example-Mods = class only no dex
- Example-Mods-Dexed = class and dex

### Feature

- Edit the gradle.properties instead of `mod.hjson`

- Editing Changelog.md will affect the release description

- Automatically create a new draft everytime you push 
