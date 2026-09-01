# KSP-patches
 A collection of random patches for Kerbal Space Program.

## Installation
 First install PatchManager manually or via CKAN.
 Then, download the latest version of CaliperPatches from the GitHub releases page. Extract into your KSP gamedata folder. Then, start the game and select the patches you want to use via PatchManager's UI.

In-game you will see two sets of patches, the content of which are detailed below:

## Recommended
 This menu contains the main patches, which are designed to be used together and are generally applicable to most play-styles. 
 Contains:
### FFTFusionRework
 This patch changes around the fuels used by FFT fusion reactors and engines, mitigating the over-reliance on D-He3. It adds D-T and He3-breeder modes to the power reactors, swaps the mirror-cell engine to use D-T, and completely revamps the laser ICF to use D-D with a hydrogen afterburner mode. It also removes the alternate D-He3 mode from the intertial-magnetic engine.
### MKS-EL-Buff
 A very simple patch to improve the productivity factors of Modular Kolonization Systems workshops when Extraplanetary Launchpads is installed.
### MPD_LH2
 Adds an alternate mode to the magnetoplasmadynamic drives from Near Future Propulsion, allowing them to use liquid hydrogen as reaction mass. When doing this they get custom Waterfall plumes, and gain some specific impulse at the cost of some thrust compared to the lithium-burning mode.
### FFT_BCAM
 Changes Far Future Technologies' endgame antimatter torch to more closely resemble the real antimatter beam core concept. Increases the ISP of the drive, and also increases the density of antimatter to equal that of liquid hydrogen (FFT already increases the density compared to CRP defualt)

May cause issues with other mods that utilize the CRP antimatter resource, but works great with any that follow FFT conventions, such as Sterling Systems or Silly Photon Drives.
 
## Extra
 This menu contains more niche patches that change gameplay more drastically. Some may conflict with each other, and with the recommended patches. Take care when using these.
 
### FFTamatNerf
 Nerfs the resource consumption and production rate of the FFT antimatter factory part by 50,000x. By default the antimatter factory is outrageously overpowered, capable of creating planet-cracking amounts of antimatter in mere minutes for essentially free. This patch makes antimatter an actually expensive resource, requiring the player to build and maintain large production stations/bases if they wish to use the endgame drives. 

Also includes a 5,000x nerf to the accelerator complex from Kerbal Colonies Industrial Processes, making it work as well as an array of 10 antimatter factory parts.

### NREParts
 Adds new placeholder parts for the Nodel Realms Explorer engines from Kerbal: Mostly Harmless. Unlike the default one these have some degree of balance (stats taken from Elite: Dangerous), but it has not been updated recently and may need more tweaking.

### WarpDriveMorePower
 Quick patch to KSP WarpDrive that increases the containment field power stat for all drives. This allows the engines to charge up 10x quicker, but also require 10x more energy. 

### MassEffectSmall
 Adds smaller parts for the Mass Effect Drive KSP mod, and also includes a way to discharge the flux resource in a similar way to StaticCharge from the Wild Blue mods. Planned to be reworked soon.

### ImpulseNerf
 Nerfs the ISP of the impulse drives from Impulse Party. The engines are still wildly unrealistic, but no longer as overwhelmingly overpowered.

## Non-Release Folders
The repository also contains some patches that have not been added to the release. These are even more experimental, and should only be used if you know what you're doing.
 
### Deprecated
 These patches are no longer being developed or maintained. They are not guaranteed to work, and are mostly retained in case I decide to revisit the concepts.

### Extra
 Patches that should work, but haven't been brought into the release yet. Some may conflict with patches in the release version. Split into subfolders by mod developer/constellation

### In-Development
 Patches still in active development. Likely will not function as intended, run only in test saves.
  