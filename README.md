# ImprovedMill
[size=3]Improves the mill by allowing it to process Corn and Amaranth into Flour and/or Sugar. Highly configurable. Players can tweak how much sugar or flour is provided by a given input though some defaults are provided.[/size]

[img]https://puu.sh/yUzjL/f0dc23a62a.png[/img]
[color=#6aa84f][size=3][b]Compatible with Stardew Valley 1.2 on Linux, Mac, and Windows. Tested on SMAPI 2.0+ but may work on earlier versions.

[/b][/size][/color][size=5]Install
[/size][size=3]1. [/size][url=https://smapi.io/]Install the latest version of SMAPI[/url][size=3].[/size]
[size=3]2. Unzip the mod folder into [/size][font=Courier New]Stardew Valley/Mods[/font][size=3].[/size]
[size=3]3. Run the game using SMAPI.[/size]

[size=5]Future Plans[/size]
[size=2](In order of priority)
[/size][size=3]0. Open source mod on github so everyone can see my terrible code. ([color=#00ff00]Tomorrow[/color])[/size]
[size=3]1. Get mod working for Wheat and Beets ([color=#93c47d]85%[/color]).
2. Add "Corn Flour", "Corn Sugar" and "Amaranth Flour" to the game. ([color=#a61c00]0%[/color])
3. Modify current recipes, where it makes sense, to accept multiple types of flour or sugar. i.e. Tortillas made from corn flower. Pink cake less so. ([color=#a61c00]0%[/color])
4. Add new recipes into the game to showcase "Corn Flour", "Corn Sugar", and "Amaranth Flour". ([color=#a61c00]0%[/color])
5. Open to suggestions.[/size]

[size=5]The config.json[/size]
[size=1](if you do not have a config.json file run SMAPI once and it will be created)
[/size][size=3]{
  "ProcessCorn": true,       -- Allows the mill to accept and process corn.
  "SugarForCorn": 1.5,      -- Amount of sugar produced from a single unit of corn. 
  "FlourForCorn": 1.5,          -- Amount of flour produced from a single unit of corn. 
  "ProcessWheat": false,   -- Allows the mod to change how wheat is processed. [color=#ff0000]*currently not working*[/color]
  "SugarForWheat": 0.0,   -- Amount of sugar produced from a single unit of wheat. [color=#ff0000]*currently not working*[/color]
  "FlourForWheat": 1.0,    -- Amount of flour produced from a single unit of wheat. [color=#ff0000]*currently not working*[/color]
  "ProcessAmaranth": true,  -- Allows the mill to accept and process Amaranth.
  "SugarForAmaranth": 0.0, -- Amount of sugar produced for a single unit of amaranth.
  "FlourForAmaranth": 2.0, -- Amount of flour produced for a single unit of amaranth.
  "ProcessBeet": false,    -- Allows the mod to change how beets are processed. [color=#ff0000]*currently not working*[/color]
  "SugarForBeet": 3.0,   -- Amount of sugar produced from a single unit of beets. [color=#ff0000]*currently not working*[/color]
  "FlourForBeet": 0.0   -- Amount of flour produced from a single unit of beets. [color=#ff0000]*currently not working*[/color]
}[/size]

[size=4]Current known bugs:[/size]
[size=3]The base game mill processes wheat and beets before the mod gets a chance too making the mod not able to modify them at the moment.[/size]

[size=5]Release Notes
[/size][size=3]Version 1.0.2: Added UpdateKey for nexus.[/size]
[size=3]Version 1.0.1: First public release.[/size]
