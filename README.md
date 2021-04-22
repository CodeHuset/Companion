# Companion Mod (Forge 1.12.2 - Pixelmon 8.1.2c)

Companion is a simple utility mod for Pixelmon 8.1.2c. It can be used in both Technic Launcher and Forge installs of Pixelmon

## Installation
```ldif

 1: Download the Companion.jar file
 2: Move it to your mods folder
  a: If you're using Technic, the path is (Windows) %appdata%\.technic\modpacks\<your-pixelmon-install>\mods
  b: If you're using Forge, the path is (Windows) %appdata%\.minecraft\mods
 3: Run your install of Pixelmon, the mod will activate and appear in Active Mods

```

## Commands
There are `two` sets of commands in Companion. Those that work **everywhere** and those that only work on a server *NOT* associated with [ComplexGaming](https://mc-complex.com) (Note: Companion is not sponsored by, supported by, endorsed by or otherwise associated with Complex Gaming.

Commands that work everywhere are prefixed with `-`. Commands that will not work on Complex Servers begin with `:`

`-help` - Displays the Help messages

`-goto subserver` - For quick switching on Complex servers (Colors/Rivals server names accepted)

`-setad <message>` - Sets a message for when you send the `-ad` command.

`-ad` - Send the message set in `-setad`

`-rcs <count> <cost>` - Sell <count> stacks of Items on a GTS for <cost> per stack. Requires a rank that has no cooldown period between messages

`-title` - Set the Display Window title. Use `%mc%` for Current Username, and `%ip%` for Current Server IP

`-remind <duration> <message>` - Set a reminder for a duration. Duration must be in a format of "1H32M" (No spaces)


Commands for Anywhere other than Complex:

`:help` - Display the Help Messages for Cheats

`:uuid` - Random command, displays YOUR UUID

`:tm` - Get the Move for a TM, using format `:tm70` to return `Flash`

`:e <pokemon>` - Get the Egg Type for the given pokemon.

`:fm <message>` - Generate a FAKE message, using standard Minecraft Color Codes



## Non Command/Cheaty stuff:

GUI elements: 
- Current server (Complex, used with -goto)
- Current User
- Item in Hand
- Durability of said Item
- World Info:
  - WorldType
  - Biome
- Coordinates
- IRL Time
- Uptime (How long the Client has been running)
- Connected Time (When used with -goto on Complex, shows time on said Server)
