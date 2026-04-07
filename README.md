----------------------------

# MINECRAFT MODPACK BACKLOG (1.21.1 NeoForge)
<style> table { width: 100%; table-layout: fixed; } </style>
----------------------------

#### LEGEND (Status):
  |      | Definition | Notes                                                        |
|:----:|:---------- | ------------------------------------------------------------ |
| [✅]  | Verified   | was installed and quick test verification ONLY               |
| [☑]  | Installed  | was installed but have not ran to see if any conflicts arise |
| [❎]  | Conflict   | was installed and failed on the quick test                   |
| [🟩] | Backlog    | Not Yet Installed (But Plan to or is considering)            |

#### LEGEND (Type):

|     | Definition | Notes                                                                                                                                          |
|:---:| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| ❖   | Dependency | Was either verified through test or mod description that it is required by another mod                                                         |
| ◆   | Standalone | A mod that works alone (excluding the requirement of the mod loader) [Exlude Libraries as they aren't installed when unused as to avoid bloat] |
| ◇   | Dependent  | Was either verified through test or mod description that it requires another mod                                                               |
| ◉   | Unsure     | No available description on its dependency and has not yet been tested on wether it requires a mod to function                                 |

#### Legend (Category):

|                           | Definition                                      |
|:-------------------------:|:----------------------------------------------- |
| Optimization / Generation | System layer / Performance                      |
| Primary                   | Independent gameplay features (Content Pillars) |
| Secondary / Add-Ons       | Mods that enhance or bridge Primary mods        |
| Aesthetics                | Visual/Audio polish (Safest to remove for FPS)  |
| Others                    | Utility, UI, or Unsorted                        |

*(Example: ❖◆ means it is both a standalone mod and a dependency)*

----------------------------

## SECTION I: CURRENT (INSTALLED & VERIFIED)

*(Dependents Tab lists all mods that depend on it. If the listed mod is enclosed by a brace like [Mod Name] then it means it is not a hard requirement but functionalities may be unavailable unless installed)*

#### Category: Optimization / Generation

| Status | Type | Mod Name                                      | Link                                                  | Dependents                 | Notes |
|:------:|:----:|:--------------------------------------------- |:----------------------------------------------------- | -------------------------- |:----- |
| [✅]    | ◆    | BadOptimizations                              | [Modrinth](https://modrinth.com/mod/badoptimizations) |                            |       |
| [✅]    | ◆    | Concurrent Chunk Management Engine (NeoForge) | [Modrinth](https://modrinth.com/mod/c2me-neoforge)    |                            |       |
| [✅]    | ◆❖   | Embeddium                                     | [Modrinth](https://modrinth.com/mod/embeddium)        | Embeddium (Rubidium) Extra |       |
| [✅]    | ◆    | Entity Culling                                | [Modrinth](https://modrinth.com/mod/entityculling)    |                            |       |
| [✅]    | ◆    | FerriteCore                                   | [Modrinth](https://modrinth.com/mod/ferrite-core)     |                            |       |
| [✅]    | ◆    | ImmediatelyFast                               | [Modrinth](https://modrinth.com/mod/immediatelyfast)  |                            |       |
| [✅]    | ◆    | KryptonFoxified                               | [Modrinth](https://modrinth.com/mod/krypton-foxified) |                            |       |
| [✅]    | ◆    | ModernFix                                     | [Modrinth](https://modrinth.com/mod/modernfix)        |                            |       |
| [✅]    | ◆    | Radium                                        | [Modrinth](https://modrinth.com/mod/radium)           |                            |       |

#### Category: Primary

| Status | Type | Mod Name                 | Link                                                         | Dependents | Notes |
|:------:|:----:| ------------------------ | ------------------------------------------------------------ | ---------- | ----- |
| [✅]    | ◆    | EMI                      | [Modrinth](https://modrinth.com/mod/emi)                     |            |       |
| [✅]    | ◆    | Just Enough Items (JEI)  | [Modrinth](https://modrinth.com/mod/jei)                     |            |       |
| [✅]    | ◇    | Sophisticated Backpack   | [Modrinth](https://modrinth.com/mod/sophisticated-backpacks) |            |       |
| [✅]    | ❖    | Sophisticated Core       | [Modrinth](https://modrinth.com/mod/sophisticated-core)      |            |       |
| [✅]    | ◇    | Sophisticated Storage    | [Modrinth](https://modrinth.com/mod/sophisticated-storage)   |            |       |
| [✅]    | ◆    | Tom's Simple Storage Mod | [Modrinth](https://modrinth.com/mod/toms-storage)            |            |       |
| [✅]    | ◆    | Tom's Trading Network    | [Modrinth](https://modrinth.com/mod/toms-trading-network)    |            |       |

#### Category: Secondary / Add-Ons

| Status | Type | Mod Name                   | Link                                                | Dependents | Notes |
|:------:|:----:| -------------------------- | --------------------------------------------------- | ---------- | ----- |
| [✅]    | ◇    | Embeddium (Rubidium) Extra | [Modrinth](https://modrinth.com/mod/rubidium-extra) |            |       |

#### Category: Asthetics

| Status | Type | Mod Name | Link | Dependents | Notes |
| ------ |:----:| -------- | ---- | ---------- | ----- |
|        |      |          |      |            |       |

#### Category: Others

| Status | Type | Mod Name         | Link                                               | Dependents   | Notes |
|:------:|:----:| ---------------- | -------------------------------------------------- | ------------ | ----- |
| [✅]    | ◆    | Cloth Config API | [Modrinth](https://modrinth.com/mod/cloth-config)  | Spell Engine |       |
| [✅]    | ◆    | Configuration    | [Modrinth](https://modrinth.com/mod/configuration) |              |       |
| [✅]    | ◆    | NeOculus         | [Modrinth](https://modrinth.com/mod/neoculus)      |              |       |
|        |      |                  |                                                    |              |       |

----------------------------

## SECTION II: BACKLOG (PLANNED)

*(Dependents Tab lists all mods that depend on it. If the listed mod is enclosed by a brace like [Mod Name] then it means it is not a hard requirement but functionalities may be unavailable unless installed)*

#### Category: Optimization / Generation

| Status | Type | Mod Name                        | Link                                                          | Dependents   | Notes                                                                          |
|:------:|:----:|:------------------------------- |:------------------------------------------------------------- | ------------ |:------------------------------------------------------------------------------ |
| [🟩]   | ❖    | Forgified Fabric API            | [Modrinth](https://modrinth.com/mod/forgified-fabric-api)     | Spell Engine | Additional Requirement on Neoforge<br/>Forge x Fabric Interoperability Library |
| [🟩]   | ◇    | Accessories Compatibility Layer | [Modrinth](https://modrinth.com/mod/accessories-compat-layer) |              | Compatability Layer                                                            |

#### Category: Primary

| Status | Type | Mod Name                        | Link                                                                          | Dependents                                                                                                                                    | Notes                                          |
|:------:|:----:| ------------------------------- | ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| [🟩]   | ◆    | Create                          | [Modrinth](https://modrinth.com/mod/create)                                   |                                                                                                                                               |                                                |
| [🟩]   | ◆    | Applied Energistics 2           | [Modrinth](https://modrinth.com/mod/ae2)                                      |                                                                                                                                               |                                                |
| [🟩]   | ◇    | Apotheosis                      | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/apotheosis)         |                                                                                                                                               |                                                |
| [🟩]   | ❖    | Placebo                         | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/placebo)            | Apotheosis                                                                                                                                    | Library Mod                                    |
| [🟩]   | ❖    | Apothic Attributes              | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/apothic-attributes) | Apotheosis                                                                                                                                    | Library Mod                                    |
| [🟩]   | ❖    | Apothic Spawners                | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/apothic-spawners)   | Apotheosis                                                                                                                                    | Module [Spawner]                               |
| [🟩]   | ❖    | Apothic Enchanting              | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/apothic-enchanting) | Apotheosis                                                                                                                                    | Module [Enchantments]                          |
| [🟩]   | ◉    | ProjectE                        | [Curse](https://www.curseforge.com/minecraft/mc-mods/projecte)                |                                                                                                                                               |                                                |
| [🟩]   | ◉    | Rechiseled                      | [Modrinth](https://modrinth.com/mod/rechiseled)                               |                                                                                                                                               | Adds many block variants                       |
| [🟩]   | ◉    | Dark Utilities                  | [Modrinth](https://modrinth.com/mod/dark-utilities)                           |                                                                                                                                               |                                                |
| [🟩]   | ❖    | Bookshelf                       | [Modrinth](https://modrinth.com/mod/bookshelf-lib)                            | Dark Utilities                                                                                                                                | Library Mod                                    |
| [🟩]   | ◉    | Farmer's Delight                | [Modrinth](https://modrinth.com/mod/farmers-delight)                          |                                                                                                                                               |                                                |
| [🟩]   | ◇    | Wizards (RPG Series)            | [Modrinth](https://modrinth.com/mod/wizards)                                  |                                                                                                                                               |                                                |
| [🟩]   | ◇    | Jewelry (RPG Series)            | [Modrinth](https://modrinth.com/mod/jewelry)                                  |                                                                                                                                               |                                                |
| [🟩]   | ◇    | Paladins & Priests (RPG Series) | [Modrinth](https://modrinth.com/mod/paladins-and-priests)                     |                                                                                                                                               |                                                |
| [🟩]   | ◇    | Archers (RPG Series)            | [Modrinth](https://modrinth.com/mod/archers)                                  |                                                                                                                                               |                                                |
| [🟩]   | ◇    | Gazebos (RPG Series)            | [Modrinth](https://modrinth.com/mod/gazebos)                                  |                                                                                                                                               |                                                |
|        | ◇    | Rogues & Wariors (RPG Series)   | [Modrinth](https://modrinth.com/mod/rogues-and-warriors)                      |                                                                                                                                               |                                                |
| [🟩]   | ❖    | Ranged Weapon API               | [Modrinth](https://modrinth.com/mod/ranged-weapon-api)                        | Archers (RPG Series)<br/>Jewelry (RPG Series)                                                                                                 | Library Mod                                    |
| [🟩]   | ❖    | AzureLib Armor                  | [Modrinth](https://modrinth.com/mod/azurelib-armor)                           | Archers (RPG Series)<br/>Paladins & Priests (RPG Series)<br/>Rogues & Wariors (RPG Series)<br/>Wizards (RPG Series)                           | Library Mod (Sripped-Down AzureLib)            |
| [🟩]   | ❖    | Runes                           | [Modrinth](https://modrinth.com/mod/runes)                                    | Paladins & Priests (RPG Series)<br/>Wizards (RPG Series)                                                                                      | The Runes Item in RPG Series                   |
| [🟩]   | ◇❖   | Spell Engine                    | [Modrinth](https://modrinth.com/mod/spell-engine)                             | Archers (RPG Series)<br/>Gazebos (RPG Series)<br/> Paladins & Priests (RPG Series)<br/>Rogues & Wariors (RPG Series)<br/>Wizards (RPG Series) | Library Mod                                    |
| [🟩]   | ❖    | Spell Power Attributes          | [Modrinth](https://modrinth.com/mod/spell-power)                              | Spell Engine<br/>Jewelry (RPG Series)                                                                                                         | Library Mod                                    |
| [🟩]   | ❖    | Curios API                      | [Modrinth](https://modrinth.com/mod/curios)                                   | Accessories Compatibility Layer                                                                                                               | Library Mod                                    |
| [🟩]   | ❖    | Trinkets                        | [Modrinth](https://modrinth.com/mod/trinkets)                                 | Accessories Compatibility Layer                                                                                                               | Library Mod<br/>Only if Fabric mods are added. |

#### Category: Secondary / Add-Ons

| Status | Type | Mod Name                           | Link                                                   | Dependents                                       | Notes                |
|:------:|:----:| ---------------------------------- | ------------------------------------------------------ | ------------------------------------------------ | -------------------- |
| [🟩]   | ◆❖   | Accessories                        | [Modrinth](https://modrinth.com/mod/accessories)       | Spell Engine<br/>Accessories Compatibility Layer |                      |
| [🟩]   | ◆    | Jade 🔍                            | [Modrinth](https://modrinth.com/mod/jade)              | Jade Addons (Neo/Forge)                          |                      |
| [🟩]   | ◇    | Jade Addons (Neo/Forge)            | [Modrinth](https://modrinth.com/mod/jade-addons-forge) |                                                  | Adds Mod Integration |
| [🟩]   | ◆    | LambDynamicLights - Dynamic Lights | [Modrinth](https://modrinth.com/mod/lambdynamiclights) |                                                  |                      |

#### Category: Asthetics

| Status | Type | Mod Name                 | Link                                                          | Dependents       | Notes       |
|:------:|:----:| ------------------------ | ------------------------------------------------------------- | ---------------- | ----------- |
| [🟩]   | ❖    | playerAnimator           | [Modrinth](https://modrinth.com/mod/playeranimator)           | Spell Engine     | Library Mod |
| [🟩]   | ❖    | bendy-lib                | [Modrinth](https://modrinth.com/mod/bendy-lib)                | [playerAnimator] | Library Mod |
| [🟩]   | ◉    | Not Enough Animations    | [Modrinth](https://modrinth.com/mod/not-enough-animations)    |                  |             |
| [🟩]   | ◉    | 3D Skin Layers           | [Modrinth](https://modrinth.com/mod/3dskinlayers)             |                  |             |
| [🟩]   | ◆    | Sound Physics Remastered | [Modrinth](https://modrinth.com/mod/sound-physics-remastered) |                  |             |

#### Category: Others

| Status | Type | Mod Name       | Link                                                                                                                   | Dependents     | Notes                  |
|:------:|:----:| -------------- |:---------------------------------------------------------------------------------------------------------------------- | -------------- | ---------------------- |
| [🟩]   | ❖    | Patchouli      | [Modrinth](https://modrinth.com/mod/patchouli) or [CurseForge](https://www.curseforge.com/minecraft/mc-mods/patchouli) | [Apotheosis]   |                        |
| [🟩]   | ◆❖   | Runelic        | [Modrinth](https://modrinth.com/mod/runelic)                                                                           | Dark Utilities | Text Compatibility Mod |
| [🟩]   | ◆❖   | Pig Pen Cipher | [Modrinth](https://modrinth.com/mod/pig-pen-cipher)                                                                    | Dark Utilities | Text Compatibility Mod |
| [🟩]   | ◆    | Mouse Tweaks   | [Modrinth](https://modrinth.com/mod/mouse-tweaks)                                                                      |                |                        |

----------------------------

## SECTION III: MASTER MOD LIST AND LINK

| Status | Type | Mod Name                                      | Creator                                                                                                                             | Link                                                                                                                    |
|:------:|:----:|:--------------------------------------------- |:----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| [✅]    | ◆    | BadOptimizations                              | [thosea](https://modrinth.com/user/thoseahttps://modrinth.com/user/thosea)                                                          | [Modrinth](https://modrinth.com/mod/badoptimizations)                                                                   |
| [✅]    | ◆    | Cloth Config API                              | [shedaniel](https://modrinth.com/user/shedaniel)                                                                                    | [Modrinth](https://modrinth.com/mod/cloth-config)                                                                       |
| [✅]    | ◆    | Concurrent Chunk Management Engine (NeoForge) | [ishland](https://modrinth.com/user/ishland)                                                                                        | [Modrinth](https://modrinth.com/mod/c2me-neoforge)                                                                      |
| [✅]    | ◆    | Configuration                                 | [Toma1O6](https://modrinth.com/user/Toma1O6)                                                                                        | [Modrinth](https://modrinth.com/mod/configuration)                                                                      |
| [✅]    | ◆❖   | Embeddium                                     | [FiniteReality](https://modrinth.com/user/FiniteReality)                                                                            | [Modrinth](https://modrinth.com/mod/embeddium)                                                                          |
| [✅]    | ◇    | Embeddium (Rubidium) Extra                    | [dima_dencep](https://modrinth.com/user/dima_dencep)                                                                                | [Modrinth](https://modrinth.com/mod/rubidium-extra)                                                                     |
| [✅]    | ◆    | EMI                                           | [Emi](https://modrinth.com/user/Emi)                                                                                                | [Modrinth](https://modrinth.com/mod/emi)                                                                                |
| [✅]    | ◆    | Entity Culling                                | [tr7zw](https://modrinth.com/user/tr7zw)                                                                                            | [Modrinth](https://modrinth.com/mod/entityculling)                                                                      |
| [✅]    | ◆    | FerriteCore                                   | [malte0811](https://modrinth.com/user/malte0811)                                                                                    | [Modrinth](https://modrinth.com/mod/ferrite-core)                                                                       |
| [✅]    | ◆    | ImmediatelyFast                               | [RaphiMC](https://modrinth.com/user/RaphiMC)                                                                                        | [Modrinth](https://modrinth.com/mod/immediatelyfast)                                                                    |
| [✅]    | ◆    | Just Enough Items (JEI)                       | [mezz](https://modrinth.com/user/mezz)                                                                                              | [Modrinth](https://modrinth.com/mod/jei)                                                                                |
| [✅]    | ◆    | KryptonFoxified                               | [TexTrue](https://modrinth.com/user/TexTrue)                                                                                        | [Modrinth](https://modrinth.com/mod/krypton-foxified)                                                                   |
| [✅]    | ◆    | ModernFix                                     | [embeddedt](https://modrinth.com/user/embeddedt)                                                                                    | [Modrinth](https://modrinth.com/mod/modernfix)                                                                          |
| [✅]    | ◆    | NeOculus                                      | [Yuqi154](https://modrinth.com/user/Yuqi154)                                                                                        | [Modrinth](https://modrinth.com/mod/neoculus)                                                                           |
| [✅]    | ◉    | Radium                                        | [Asek3](https://modrinth.com/user/Asek3)                                                                                            | [Modrinth](https://modrinth.com/mod/radium)                                                                             |
| [✅]    | ◇    | Sophisticated Backpack                        | [P3pp3rF1y](https://modrinth.com/user/P3pp3rF1y)                                                                                    | [Modrinth](https://modrinth.com/mod/sophisticated-backpacks)                                                            |
| [✅]    | ❖    | Sophisticated Core                            | [P3pp3rF1y](https://modrinth.com/user/P3pp3rF1y)                                                                                    | [Modrinth](https://modrinth.com/mod/sophisticated-core)                                                                 |
| [✅]    | ◇    | Sophisticated Storage                         | [P3pp3rF1y](https://modrinth.com/user/P3pp3rF1y)                                                                                    | [Modrinth](https://modrinth.com/mod/sophisticated-storage)                                                              |
| [✅]    | ◆    | Tom's Simple Storage Mod                      | [Tom5454](https://modrinth.com/user/tom5454)                                                                                        | [Modrinth](https://modrinth.com/mod/toms-storage)                                                                       |
| [✅]    | ◆    | Tom's Trading Network                         | [Tom5454](https://modrinth.com/user/tom5454)                                                                                        | [Modrinth](https://modrinth.com/mod/toms-trading-network)                                                               |
| [🟩]   | ◆    | Create                                        | [simibubi](https://modrinth.com/user/simibubi)                                                                                      | [Modrinth]()                                                                                                            |
| [🟩]   | ◆    | Applied Energistics 2                         | [shartte](https://modrinth.com/user/shartte)                                                                                        | [Modrinth]()                                                                                                            |
| [🟩]   | ◇    | Apotheosis                                    | [Shadows_of_Fire](https://www.curseforge.com/members/shadows_of_fire/projects)                                                      | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/apotheosis)                                                   |
| [🟩]   | ❖    | Placebo                                       | [Shadows_of_Fire](https://www.curseforge.com/members/shadows_of_fire/projects)                                                      | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/placebo)                                                      |
| [🟩]   | ❖    | Apothic Attributes                            | [Shadows_of_Fire](https://www.curseforge.com/members/shadows_of_fire/projects)                                                      | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/apothic-attributes)                                           |
| [🟩]   | ❖    | Apothic Spawners                              | [Shadows_of_Fire](https://www.curseforge.com/members/shadows_of_fire/projects)                                                      | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/apothic-spawners)                                             |
| [🟩]   | ❖    | Apothic Enchanting                            | [Shadows_of_Fire](https://www.curseforge.com/members/shadows_of_fire/projects)                                                      | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/apothic-enchanting)                                           |
| [🟩]   | ❖    | Patchouli                                     | [Vazkii (Modrinth)](https://modrinth.com/user/Vazkii)<br/>[Vazkii (CurseForge)](https://www.curseforge.com/members/vazkii/projects) | [Modrinth](https://modrinth.com/mod/patchouli)<br/>[CurseForge](https://www.curseforge.com/minecraft/mc-mods/patchouli) |
| [🟩]   | ◉    | ProjectE                                      | [SinKillerJ](https://www.curseforge.com/members/sinkillerj/projects)                                                                | [Curse](https://www.curseforge.com/minecraft/mc-mods/projecte)                                                          |
| [🟩]   | ◉    | Rechiseled                                    | [SuperMartijn642](https://modrinth.com/user/SuperMartijn642)                                                                        | [Modrinth](https://modrinth.com/mod/rechiseled)                                                                         |
| [🟩]   | ◉    | Dark Utilities                                | [Darkhax](https://modrinth.com/user/Darkhax)                                                                                        | [Modrinth](https://modrinth.com/mod/dark-utilities)                                                                     |
| [🟩]   | ❖    | Bookshelf                                     | [Darkhax](https://modrinth.com/user/Darkhax)                                                                                        | [Modrinth](https://modrinth.com/mod/bookshelf-lib)                                                                      |
| [🟩]   | ◆❖   | Runelic                                       | [Darkhax](https://modrinth.com/user/Darkhax)                                                                                        | [Modrinth](https://modrinth.com/mod/runelic)                                                                            |
| [🟩]   | ◆❖   | Pig Pen Cipher                                | [Darkhax](https://modrinth.com/user/Darkhax)                                                                                        | [Modrinth](https://modrinth.com/mod/pig-pen-cipher)                                                                     |
| [🟩]   | ◉    | Farmer's Delight                              | [vectorwing](https://modrinth.com/user/vectorwing)                                                                                  | [Modrinth](https://modrinth.com/mod/farmers-delight)                                                                    |
| [🟩]   | ❖    | AzureLib Armor                                | [AzureDoom](https://modrinth.com/user/AzureDoom)                                                                                    | [Modrinth](https://modrinth.com/mod/azurelib-armor)                                                                     |
| [🟩]   | ❖    | Runes                                         | [ZsoltMolnarrr](https://modrinth.com/user/ZsoltMolnarrr)                                                                            | [Modrinth](https://modrinth.com/mod/runes)                                                                              |
| [🟩]   | ❖    | playerAnimator                                | [KosmX](https://modrinth.com/user/KosmX)                                                                                            | [Modrinth](https://modrinth.com/mod/playeranimator)                                                                     |
| [🟩]   | ❖    | bendy-lib                                     | [KosmX](https://modrinth.com/user/KosmX)                                                                                            | [Modrinth](https://modrinth.com/mod/bendy-lib)                                                                          |
| [🟩]   | ◇❖   | Spell Engine                                  | [ZsoltMolnarrr](https://modrinth.com/user/ZsoltMolnarrr)                                                                            | [Modrinth](https://modrinth.com/mod/spell-engine)                                                                       |
| [🟩]   | ❖    | Spell Power Attributes                        | [ZsoltMolnarrr](https://modrinth.com/user/ZsoltMolnarrr)                                                                            | [Modrinth](https://modrinth.com/mod/spell-power)                                                                        |
| [🟩]   | ❖    | Forgified Fabric API                          | [Sinytra](https://modrinth.com/organization/sinytra)                                                                                | [Modrinth](https://modrinth.com/mod/forgified-fabric-api)                                                               |
| [🟩]   | ◆❖   | Accessories                                   | [glisco](https://modrinth.com/user/glisco)                                                                                          | [Modrinth](https://modrinth.com/mod/accessories)                                                                        |
| [🟩]   | ❖    | Accessories Compatibility Layer               | [Blodhgarm](https://modrinth.com/user/Blodhgarm)                                                                                    | [Modrinth](https://modrinth.com/mod/accessories-compat-layer)                                                           |
| [🟩]   | ❖    | Curios API                                    | [TheIllusiveC4](https://modrinth.com/user/TheIllusiveC4)                                                                            | [Modrinth](https://modrinth.com/mod/curios)                                                                             |
| [🟩]   | ❖    | Trinkets                                      | [Emi](https://modrinth.com/user/Emi)                                                                                                | [Modrinth](https://modrinth.com/mod/trinkets)                                                                           |
| [🟩]   | ❖    | Ranged Weapon API                             | [ZsoltMolnarrr](https://modrinth.com/user/ZsoltMolnarrr)                                                                            | [Modrinth](https://modrinth.com/mod/ranged-weapon-api)                                                                  |
| [🟩]   | ◇    | Wizards (RPG Series)                          | [ZsoltMolnarrr](https://modrinth.com/user/ZsoltMolnarrr)                                                                            | [Modrinth](https://modrinth.com/mod/wizards)                                                                            |
| [🟩]   | ◇    | Jewelry (RPG Series)                          | [ZsoltMolnarrr](https://modrinth.com/user/ZsoltMolnarrr)                                                                            | [Modrinth](https://modrinth.com/mod/jewelry)                                                                            |
| [🟩]   | ◇    | Paladins & Priests (RPG Series)               | [ZsoltMolnarrr](https://modrinth.com/user/ZsoltMolnarrr)                                                                            | [Modrinth](https://modrinth.com/mod/paladins-and-priests)                                                               |
| [🟩]   | ◇    | Archers (RPG Series)                          | [ZsoltMolnarrr](https://modrinth.com/user/ZsoltMolnarrr)                                                                            | [Modrinth](https://modrinth.com/mod/archers)                                                                            |
| [🟩]   | ◇    | Gazebos (RPG Series)                          | [ZsoltMolnarrr](https://modrinth.com/user/ZsoltMolnarrr)                                                                            | [Modrinth](https://modrinth.com/mod/gazebos)                                                                            |
| [🟩]   | ◇    | Rogues & Wariors (RPG Series)                 | [ZsoltMolnarrr](https://modrinth.com/user/ZsoltMolnarrr)                                                                            | [Modrinth](https://modrinth.com/mod/rogues-and-warriors)                                                                |
| [🟩]   | ◉    | Not Enough Animations                         | [tr7zw](https://modrinth.com/user/tr7zw)                                                                                            | [Modrinth](https://modrinth.com/mod/not-enough-animations)                                                              |
| [🟩]   | ◉    | 3D Skin Layers                                | [tr7zw](https://modrinth.com/user/tr7zw)                                                                                            | [Modrinth](https://modrinth.com/mod/3dskinlayers)                                                                       |
| [🟩]   | ◆    | Jade 🔍                                       | [Snownee](https://modrinth.com/user/Snownee)                                                                                        | [Modrinth](https://modrinth.com/mod/jade)                                                                               |
| [🟩]   | ◇    | Jade Addons (Neo/Forge)                       | [Snownee](https://modrinth.com/user/Snownee)                                                                                        | [Modrinth](https://modrinth.com/mod/jade-addons-forge)                                                                  |
| [🟩]   | ◆    | Mouse Tweaks                                  | [YaLTeR](https://modrinth.com/user/YaLTeR)                                                                                          | [Modrinth](https://modrinth.com/mod/mouse-tweaks)                                                                       |
| [🟩]   | ◆    | Sound Physics Remastered                      | [henkelmax](https://modrinth.com/user/henkelmax)                                                                                    | [Modrinth](https://modrinth.com/mod/sound-physics-remastered)                                                           |
| [🟩]   | ◆    | LambDynamicLights - Dynamic Lights            | [LambdAurora](https://modrinth.com/user/LambdAurora)                                                                                | [Modrinth](https://modrinth.com/mod/lambdynamiclights)                                                                  |
| [🟩]   | ◉    | No Chat Reports                               | Aizistral                                                                                                                           |                                                                                                                         |
| [🟩]   | ◉    | Chat Heads                                    | dzwdz                                                                                                                               |                                                                                                                         |
| [🟩]   | ◉    | Simple Voice Chat                             | [henkelmax](https://modrinth.com/user/henkelmax)                                                                                    |                                                                                                                         |
| [🟩]   | ◉    | Essential Mod                                 | SparkUniverse                                                                                                                       |                                                                                                                         |
| [🟩]   | ◉    | Cherished Worlds                              | [TheIllusiveC4](https://modrinth.com/user/TheIllusiveC4)                                                                            |                                                                                                                         |
| [🟩]   | ◉    | Polymorph                                     | [TheIllusiveC4](https://modrinth.com/user/TheIllusiveC4)                                                                            |                                                                                                                         |
| [🟩]   | ◉    | Visual Workbench                              | Fuzs                                                                                                                                |                                                                                                                         |
| [🟩]   | ◉    | Cut Through                                   | Fuzs                                                                                                                                |                                                                                                                         |
| [🟩]   | ◉    | Mutant Monsters                               | Fuzs                                                                                                                                |                                                                                                                         |
| [🟩]   | ◉    | Diagonal Windows                              | Fuzs                                                                                                                                |                                                                                                                         |
| [🟩]   | ◉    | Diagonal Fences                               | Fuzs                                                                                                                                |                                                                                                                         |
| [🟩]   | ◉    | Leaves Be Gone                                | Fuzs                                                                                                                                |                                                                                                                         |
| [🟩]   | ◉    | Trading Post                                  | Fuzs                                                                                                                                |                                                                                                                         |
| [🟩]   | ◉    | Magnum Torch                                  | Fuzs                                                                                                                                |                                                                                                                         |
| [🟩]   | ◉    | Bartering Station                             | Fuzs                                                                                                                                |                                                                                                                         |
| [🟩]   | ◉    | Diagonal Walls                                | Fuzs                                                                                                                                |                                                                                                                         |
| [🟩]   | ◉    | Lootr                                         | noobanidus                                                                                                                          |                                                                                                                         |
| [🟩]   | ◉    | Chunky                                        | pop4959                                                                                                                             |                                                                                                                         |
| [🟩]   | ◆    | Better Combat                                 | [ZsoltMolnarrr](https://modrinth.com/user/ZsoltMolnarrr)                                                                            | [Modrinth](https://modrinth.com/mod/better-combat)                                                                      |

----------------------------

## SYSTEM INFO

- Ryzen 3 3200G

- 16GB RAM 2x8GB [Allocated: 8112MB]

- Mod Loader: NeoForge

- Minecraft Version: 1.21.1
