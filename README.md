# No longer updating. Support has ended.

# Paking Guide
Download [Unrealpak](https://drive.usercontent.google.com/u/1/uc?id=1IxQaP-JVNjO1XqSvyG-VysErPH6AlhfG&export=download).
Watch this [tutorial](https://www.youtube.com/watch?v=if5k00s15C8).


## Small Mod Menu Usage

Press **J** in-game to activate the Small Mod Menu.

> [!TIP]
> Your saved config location is in: `%localappdata%\DeadByDaylight\Saved\SaveGames`

## Changing FOV and Red Stain Settings

1. Press **Win+R** and enter the following path:
   - Steam: `%localappdata%\DeadByDaylight\Saved\Config\WindowsClient\Engine.ini`
   - Epic Games: `%localappdata%\DeadByDaylight\Saved\Config\EGS\Engine.ini`
   Press **Enter**.

2. In the opened notepad window, go to the end of the file and paste the following lines:

```ini
[/Game/RedStain/RedStainSettings.RedStainSettings_C]
bCastShadows=False ; False = stain visible through walls (Default: True)
AttenuationRadius=600 ; Stain distance (Default: 450)
Intensity=25000 ; Brightness (Default: 25000)
LightColor=(R=0.75,G=0,B=0,A=1) ; Stain color (Default: R=0.75,G=0,B=0,A=1)
OuterConeAngle=40 ; Stain width (Default: 40)
InnerConeAngle=11 ; Stain width (Default: 11)

[/Game/FovController/Settings.Settings_C]
SurvivorFOV=90 ; Survivor Field of View (Default: 90)
KillerFOV=87 ; Killer Field of View (Default: 87)
```

3. Adjust values as needed and save the `Engine.ini` file.

## List of Mods in this Modpack

- Cosmetic Unlocker & Break Sets
- Some Foliage Removed
- Unlocked Locked Perk Slots
- Ignore Blindness
- SSL Bypass
- Use of Bloodpoint Offerings in KYF Mode
- Killer Detector
- Horologium Core
- Red Stain Changer
- Config Unlocker
- Small Mod Menu
- Distortion and Off the Record Bypass
- Dredge Reign of Darkness Remover
- Exclusive cosmetics as custom slots

## Donations

<a href="https://www.buymeacoffee.com/RegularLunar"><img src="https://img.buymeacoffee.com/button-api/?text=You can support me here!&emoji=&slug=RegularLunar&button_colour=804dff&font_colour=ffffff&font_family=Lato&outline_colour=ffffff&coffee_colour=FFDD00" height="40" width="250" /></a>

## Discord

Join my Discord community for discussions: [Discord](https://discord.gg/mFAxKpT457)
