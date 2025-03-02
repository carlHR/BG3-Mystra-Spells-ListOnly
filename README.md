# BG3-Mystra-Spells-ListOnly

This repository contains a HTML file which was procedurally generated using python scripts that were used to parse the mod files, extracted with bg3 modders multitool in windows. 

The file can be viewed offline. It embeds icon images with base64 encoding, and contains icon images from the game as a means of displaying spell icons within its dialogs without the need of hosting images somewhere else. For this reason, the HTML file size may be larger than usual. Around ~10MB or so.

The file embeds images downloaded from: https://bg3.wiki/, and the mod files themselves found here: https://mod.io/g/baldursgate3/m/mystras-spells.

The file is used to open up dialogs that can be dragged down on the screen, and resized at will. The file is used to tell wether a spell from this mod requires concentration, is a ritual spell, and from which class it belongs to. Each dialog displays suboptions from each spell, if it has any.

The file contains two inputs: Character Level, and Spell Mod Bonus. These inputs can be changed at will and will alter the text descriptions of opened dialogs, if they're cantrips, or use any of those parameters.

---

In order to start out, **download** the spell list, and open it with your browser. Have fun!

---

TODO:
 - Keep adding more descriptions to spells based on their source files' parameters
 - Add Status effects (this one will take me time)
