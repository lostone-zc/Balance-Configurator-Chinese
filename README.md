# BalanceConfigurator

Support language: English | [简体中文](https://github.com/Monster-Train-2-Modding-Group/Balance-Configurator/blob/main/README_zh.md)

![icon](https://raw.githubusercontent.com/Monster-Train-2-Modding-Group/Balance-Configurator/main/icon.png)

Noncosmetic mod that allows one to edit fields from BalanceData, and as an example of a mod using Trainworks Reloaded that has user editable configuration.

![starting](https://raw.githubusercontent.com/Monster-Train-2-Modding-Group/Balance-Configurator/main/screenshots/starting.png)

![relic_draft](https://raw.githubusercontent.com/Monster-Train-2-Modding-Group/Balance-Configurator/main/screenshots/relic_reward.png)
<sub>The reward for skipping an artifact was adjusted from 25 to 75 gold</sub>

![champion_upgrade](https://raw.githubusercontent.com/Monster-Train-2-Modding-Group/Balance-Configurator/main/screenshots/champion_upgrades.png)
<sub>All three champion upgrades are available! (The UI doesn't handle this well)</sub>

![deployment](https://raw.githubusercontent.com/Monster-Train-2-Modding-Group/Balance-Configurator/main/screenshots/deployment.png)
<sub>You can change ember amount and the extra deployment ember</sub>

![battle](https://raw.githubusercontent.com/Monster-Train-2-Modding-Group/Balance-Configurator/main/screenshots/battle.png)
<sub>You can change your hand size and the maximum hand size. Here its 10. Along with 5 ember</sub>

![card_draft](https://raw.githubusercontent.com/Monster-Train-2-Modding-Group/Balance-Configurator/main/screenshots/card_draft.png)
<sub>Reward for skipping card drafts can also be adjusted</sub>

## Features

 Ability to edit particular starting details of runs among other things:

* Ticket values for each rarity type for cards, enhancers (shop upgrades), and artifacts
  * Example: for enhancers the rarity tickets are Common = 70, Uncommon = 30 meaning 70% chance for common, and 30% chance for uncommon.
* Starting gold
* Maximum hand size
* Start of turn ember
* Extra ember for deployment phase
* Max ember
* Initial cap for Dragons Hoard
* Max cap for Dragons Hoard
* Start of turn hand size
* Unit Upgrade slots
* Spell Upgrade Slots
* Equipment Upgrade Slots (*not useful*)
* Maximum spawn points per floor
* Initial Unit capacity per floor
* Maximum number of mutators
* Number of champion upgrades shown
* Main class Xp factor (controls experience gained)
* Subclass Xp factor
* Alternate champion unlock level
* Gold for skipping rewards.
* (New 1.2.0) Chance of optional outpost dialogue after a run
* (New 1.2.0) Fast dialogue multiplier
* (New 1.2.0) Costs of items in shops by rarity (Cards, Enhancers, and Artifacts)

## Usage

Once installed via thunderstore or manually. The file to edit is `BalanceConfigurator.Plugin.cfg`. The default values are those used within the game. Edit to your liking.

* If installed via thunderstore. The file can be edited in the thunderstore config editor. If you want to edit the file in another text editor it should be located `C:\Users\<user>\AppData\Roaming\Thunderstore Mod Manager\DataFolder\MonsterTrain2\profiles\<test>\BepInEx\config\BalanceConfigurator.Plugin.cfg`

* If installed manually it should be placed where you installed BepinEx. Normally such an install would be placed in the same directory as the game's executable.
  `C:\Program Files (x86)\Steam\steamapps\common\Monster Train 2\BepInEx\config\BalanceConfigurator.Plugin.cfg`

## Warning

As with all non cosmetic mods and as a warning **do not** do anything online such as community challenges or the daily challenge with modded content. Getting an unfair advantage and setting a high score will surely get you banned ([Steam forums post - Don't anger ShinySteve!](https://steamcommunity.com/app/2742830/discussions/0/599653789035669752/)).

The default configuration in the mod (see usage below) is the same as how the game was configured.

The only ***probably safe*** fields you can modify without giving an yourself an unfair advantage in online play are

- main class Xp factor
- subclass Xp factor
- alternate champion unlock level

### **Important**

F8 bug reports will be disabled with this mod enabled (you can still open the menu, but submitting a report won't send it anywhere). This feature was asked for directly from Shiny Shoe and should be present in most mods. If you find a bug in the game and suspect that it isn't due to your use of mods, file a report  at [Monster Train 2 Bugs and Technical issues :: Steam Community](https://steamcommunity.com/app/2742830/discussions/1/) or on the Shiny Shoe discord.

## Lastly

We are not responsible for any unintended behavior / damage that results from using this mod. Use responsibly.
