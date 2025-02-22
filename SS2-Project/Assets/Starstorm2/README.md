
![Starstorm 2](https://github.com/swuff-star/Starstorm2/blob/main/SS2-Project/Assets/Starstorm2/ReadmeAssets/ss2logopurple.gif?raw=true)

**Starstorm 2** is a work-in-progress adaptation of the Risk of Rain 1 mod "Starstorm". It currently features three new survivors, three new monsters, over 20 new items and equipment, and numerous new challenges to shake up your runs.

![New Survivors...](https://github.com/swuff-star/Starstorm2/blob/main/SS2-Project/Assets/Starstorm2/ReadmeAssets/ss2survivorpromo.gif?raw=true)

* **Executioner**  - An aggressive, versatile survivor with an arsenal made for picking off targets and chaining kills. His powerful Ion Manipulators gain charges with every kill.

* **???** - Survivors of unknown origin, familiar yet unfamiliar. Under the right conditions, you may meet them on the Planet, but they certainly won't be on your side.

![New Items...](https://github.com/swuff-star/Starstorm2/blob/main/SS2-Project/Assets/Starstorm2/ReadmeAssets/ss2itemspromo.gif?raw=true)

* **New Items & Equipment** - A plethora of new items and equipment to support new and existing playstyles. Watch your six with an Armed Backpack, rush through teleporter events with a Field Accelerator, all while keeping on the move with a Swift Skateboard - and more!

* **New Interactables** - New drones, paired with the Refabricator, come in handy to assist you while you fight for survival.

![New Challenges...](https://github.com/swuff-star/Starstorm2/blob/main/SS2-Project/Assets/Starstorm2/ReadmeAssets/ss2challengepromo.gif?raw=true)

* **Events** - Between severe weather, magical buildups, and mysterious invaders, learn to expect the unexpected as forces both natural and supernatural interfere with your runs.

* **New Monsters** - New species of the Planet have come out to put a stop to your invasion of their home.

* **Typhoon** - The Planet grows restless, with fearsome events and monsters coming in greater numbers than ever before. Unlock new skins for survivors* by proving yourself in this new challenge exceeding even Monsoon!
	 *currently includes Commando, Huntress, MUL-T, Acrid, Captain, Executioner, and Commando's Vestige.
	 
* **Artifact of Cognation** - A new, unlockable artifact to shape up your runs.

![Credits](https://github.com/swuff-star/Starstorm2/blob/main/SS2-Project/Assets/Starstorm2/ReadmeAssets/ss2credits.gif?raw=true)

Starstorm 2 is currently being developed and maintained by...
* Buns, Nebby, orbeezeater22, swuff★, Zenithrium

With previous and one-off code contributions by...
* Anreol, bread, Flan, Gaforb, GrooveSalad, HIFU, KevinFromHPCustomerService, MagicGonads, malfaisant, Moffein, Nebby, Noop, Phreel, prod, rob, swuff★, sebacame, Shared, TheTimesweeper, Vale-X, xpcybic, Xubas

With Art/Modelling/Animation contributions by...
* Alexstarwras, Anreol, Bolty, bread, bruh, Cexeub, dotflare, Draymarc, Domi, JestAnotherAnimator, Gem, goodguy, GrooveSalad, JaceDaDorito, LucidInceptor, Neik, KevinFromHPCustomerService, PapaZach, Plexus, prodzpod, QuietAnon, rekkadraws, redacted, rob, SkeletorChampion, SOM, Spenny, swuff★, xpcybic, Reithierion, UnknownGlaze, Zenithrium

Additional thanks to... 
* Writing - Blimblam, Lyrical Endymion, rekkadraws, swuff★, T_Dimensional, Zenithrium
* Translations - Anreol, BannyDee (Spanish), MysticSword (Russian), Damglador (Ukrainian), 乃茶, Etundit, Dying_Twilight (Chinese), Kauzok (Portuguese), StyleMyk (French)
* Sound - KevinFromHPCustomerService, Neik, SOM, UnknownGlaze, NAIRB zepol
* Special thanks - Altzeus, DestroyedClone, Dee', don, Gnome, JesusPxP, KomradeSpectre, MinimalEffort, Moshinate, MysticSword, Riskka, Ruxbieno, SalvadorBunny, SlipSkip, Twiner, VioletChaolan, valerie ♥ 

## Feedback, Bug Reporting & Known Issues

Bugs can be reported at our [GitHub page](https://github.com/TeamMoonstorm/Starstorm2/issues). A list of known & previously reported issues can also be found here. Please include an [Output Log](https://h3vr-modding.github.io/wiki/installing/troubleshooting/log_file.html) and detailed steps to help recreate your error! Feedback about the modded characters pertaining to balance and gameplay can be discussed in our [Discord server](https://discord.com/invite/SgFxwKT7nY).

* Known Issues
    * Elite events are currently disabled.

## Changelog
**Warning: content spoilers below!**
### 0.6.0
* New Content
    * Survivor: Chirr.
    * Event: Empyrean Invasion.
    * Elite: Empyrean.
    * Artifact: Artifact of Havoc.
* General
    * Added ScrollableLobbyUI as a dependency.


### 0.5.7
* General
    * Added French translation. Thank you StyleMyk!
    * Survivors and monsters are better organized in the config. 
    * Fixed sweeping disables for survivors, monsters, and interactables.
    * Fixed the footstep visuals for all survivors and footstep sound effects for Executioner and Nemesis Commando.
* Nemesis Commando
    * Fixed issue with timing on primary swing. 
* Interactables
    * Refabricator can no longer spawn in Simulacrum.
* Drones
    * Restored Duplicator Drone's cooldown visuals.

### 0.5.6
* General
    * Finally finished implementing Portuguse translation.
    * Survivors and monsters can now be disabled.
    * Unfinished equipments are now entirely disabled.
    * Typhoon has been reverted to +25% spawn rate and -20% enemy rewards.
* Items
    * Hopefully fixed a Relic of Termination nullref with Refightilization.
* Nemeis Mercenary
    * Fixed an bug with Proliferate and sources of damage without an attacker.
* Monsters
    * All monsters are now properly added to the ExpansionDef. 
    * Rushroom's trail VFX now stops when it dies.
* Interactables
    * Interactables are now properly added to the ExpansionDef.

### 0.5.5
* General
    * Partially implemented Portuguse translation. 
    * Captain GM now has dithering.
* Items
    * Needles's item display now has dithering.
    * Haunted Lamp no longer drops when disabled.
    * Haunted Lamp actually fires if the follower doesn't exist.
* Executioner   
    * Fixed Execution softlocking the player when failing to land when falling out of bounds.
* Nemesis Mercenary
    * Improved blacklist for Proliferate's clone.
* Drones
    * Shock and Duplicator drones now drop purchasable interactables when destroyed.