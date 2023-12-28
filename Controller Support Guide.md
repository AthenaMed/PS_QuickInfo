---
share: "true"
---

[Keybinds](./Keybinds.md)
➡️ Controller support guide (credits to jodokh)

First of all, you need to start a new game with mouse and keyboard, and once inside, go to the settings and enable controller support.
For the Target Lock to work, you need to configure the "**Target Lock Key**" in the MCM of "**True Directional Movement**" (I set mine to pressing **RS**).

If you want to use Skyrims default implementation you are ready to go, if you want to use the mod Elden Equip there are some additional steps.

## How does Elden Equip work?
You cycle through your left hand weapons with dpad-left and your right hand weapons with dpad-right. You cycle through your spells with dpad-up. You cycle through your items with dpad-down. You assign stuff to those slots by long pressing the "**Quick Item Use Button**" (default x) and then equip or use the item in the inventory. Long press the "**Quick Item Use Button**" afterwards to exit the Edit-Mode again. 

## How do I use Elden Equip:
Enable the optional mods under "**Controller Support**" in Mod Organizer (Skyrim Platform, Elden Equip and Elden Equip Controlmap)
Configure Elden Equip in the MCM to work properly:
Change the "**Quick Item Use**" to alternate. This lets you use the selected item (cycled with dpad-down) by long pressing dpad-down. (The default mode "Normal" expects you to use the "Quick Item Use Button" which is x by default and usually does not work because it is used for other things)
Disable "**Lock Left Hand Cycle**" to be able to switch to your left hand weapon (e.g. your torch) even though you are currently wielding a two-handed weapon (in general, switching to your left hand weapon when a bow is equipped does not work)

Also long pressing the right stick switches between first and third person.
(Instructions tested on Version: 0.7.9.2)

## TKDodge Settings

➡️  To change dodge button, you have to edit TKDodge RE mod, and edit the INI file.

File location: `mods/TK Dodge RE/SKSEPlugins/TK Dodge RE.ini`

Change ``"EnableSprintKeyDodge = false"`` to ``"EnableSprintKeyDodge = true"`` 

(credits to shortround1897)