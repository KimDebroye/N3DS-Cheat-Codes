# Nintendo 2DS/3DS Cheat Codes

## Super Mario 3D Land

### Cheat Codes Overview (*All Regions & Revisions*)
****************************************************
**<details><summary>` CLICK TO SHOW/HIDE AVAILABLE CHEATS FOR THIS GAME `</summary>**
<p>

- `Play as Mario`
- `Play as Luigi`
  - *Even when game not beaten.*
- `(L+Down) Small Mario/Luigi`
- `(L+Left) Super Mario/Luigi`
- `(L+Right) Fire Mario/Luigi`
- `(L+Up) Tanooki Mario/Luigi`
- `(R+Down) Tanooki Statue Mario/Luigi`
- `(R+Right) Boomerang Mario/Luigi`
- `(R+Up) White Tanooki Mario/Luigi`
- `Always Star Power`
- `Always Tail Attack (Any Powerup)`
  - *In effect when playing a level.*
  - *In order to restore powerup defaults, disable this cheat code when not in a level.*
- `Always Flutter (Any Powerup)`
  - *In effect when playing a level.*
  - *In order to restore powerup defaults, disable this cheat code when not in a level.*
- `Moon Jump`
  - *Makes Mario/Luigi jump higher.*
  - *Code optimized for use with Luma~Rosalina's cheat engine.*
  - *Read cheat code note for use with CTRPluginFramework.*
- `(B) Infinite Jump`
  - *Allows Mario/Luigi to infinitely jump multiple times in mid-air.*
  - *Hold button to jump as high as desired.*
- `Max Lives (Three Crowns)`
- `5 Lives`
- `Infinite Time`
  - *In effect when playing a level.*
  - *In order to restore level timer default, disable this cheat code when not in a level.*
- `Start Level With P-Wing`
  - *Does not affect Shiny Stars (if any) when saving game.*
> Unlock Codes
> ------------
  - `(L+R+Up+X) Unlock All (5 Shiny Stars)`
    - *For currently opened save file:*
      - *All Normal & Special Worlds unlocked.*
      - *All Normal & Special Levels unlocked.*
      - *All Pictures collected.*
      - *All Star Coins collected.*
      - *Star Coin counter set to a reasonable number.*
      - *All requirements met for a 5 Shiny Stars save.*
    - *This code does not:*
      - *Reopen already closed Mystery Boxes or Toad Houses.*
      - *Overwrite best level times (if any).*
      - *Change any character attributes, like number of lives, current powerup, current level, etcetera.*
  - `(Keep) Open Closed Mystery Boxes`
    - *Load any save file, switch between worlds or enter any level in order for code to take effect.*
  - `(Keep) Open Closed Toad Houses`
    - *Load any save file, switch between worlds or enter any level in order for code to take effect.*

</p>
</details>

****************************************************

### General Notes:
  - All cheat codes should be optimized for all regions & revisions.
  - In order for enabled cheat codes to take effect, depending on the code enabled, <br />**some codes require you to:**
    - **Use a button combination.**
      - *These codes are marked with a * and list the button combination to be used between (parentheses).*
    - **Trigger a screen transition.** Accomplishable by, for example:
      - *Switching between Worlds on World Map (if more then one World opened).*
      - *Entering and exiting a level.*
        - *For exiting a level, any of the following options are valid:*
          - *Pause and return to map (level select).*
          - *Finish a level.*
 - In order to be successfully disabled, <br />**the following cheat codes need to be disabled when not in a level:**
	  - *Always Tail Attack (Any Powerup)*
	  - *Always Flutter (Any Powerup)*
	  - *Infinite Time*

### Installation
- [Download the latest version of the SM3DL cheat files](https://github.com/KimDebroye/N3DS-Cheat-Codes/releases/tag/SM3DL_v1.0.0).
- Running **Custom Firmware Luma3DS 9.1 or higher**:
  - Insert the SD/MicroSD card into your computer/phone.
    - *You can also use FTP if you are familiar with that.*
  - Create a folder named `cheats` on the root of your SD/MicroSD card (if it doesn't already exist).
  - Place/Overwrite the .txt file(s) containing the cheats for your game region in this folder.
    - For **Super Mario 3D Land (Europe)**:
      - *SD/MicroSD card root*/`cheats`/**0004000000053F00.txt**
    - For **Super Mario 3D Land (USA)**:
      - *SD/MicroSD card root*/`cheats`/**0004000000054000.txt**
    - For **Super Mario 3D Land (TWN)**:
      - *SD/MicroSD card root*/`cheats`/**0004000000089E00.txt**
    - For **Super Mario 3D Land (JPN)**:
      - *SD/MicroSD card root*/`cheats`/**0004000000054100.txt**
  - When transfered, eject/unmount the SD/MicroSD card from your computer/phone.
    - *Or disconnect the FTP connection.*
  - Launch the game and pull up the Rosalina menu (`L+Down+Select`).
  - Select the menu option "Cheats".
  - Select the cheats you want to activate by pressing the A button.
    - Certain cheats need additional key combinations when in game. These cheats are marked with a * and also mention the key combinations to use in order to activate the cheat.
  - Exit out of the Rosalina menu by pressing the B button until the game is back in focus.
- Happy cheating!

### Cheat Compatibility
- Compatible with
  - Old & New 2DS/3DS XL
  - Custom Firmware
    - Luma3DS 10.0.1
    - Luma3DS 9.1 (with/without CTRPF plugin loader).

### Bugs/Issues/Feedback
- No notable crashes/issues.
  - **I do however strongly recommend not to enable all cheat codes at once and occasionally disable any cheat codes that aren't of use anymore (f.e. unlock/set/reset codes, ...).**
- Should you have feedback or do encounter any issues, feel free to drop a comment in [the GBAtemp release thread](https://gbatemp.net/forums/3ds-rom-hacking-translations-and-utilities.276/).

### Software/Tools/Resources Used
- [CTRPluginFramework (by Nanquitas)](https://github.com/Nanquitas/CTRPluginFramework-BlankTemplate)
  - *Used for searching addresses/values and creating RAM dumps.*
- [Gateway RAM Tools](https://www.maxconsole.com/threads/tool-gateway-ram-tools.40776/)
  - *Used for converting RAM dumps to raw RAM dumps.*
- [TempAR](https://raing3.gshi.org/files/psp/tools/pointer_searcher.zip)
  - *Used for help with finding pointer addresses in raw RAM dumps.*
- [HxD: Freeware Hex Editor](https://mh-nexus.de/en/hxd/)
  - *Used for manually searching addresses/values/pointers by comparing and reading raw RAM dumps.*
- [SM3DL Save Editor](https://github.com/yonaikerlol/Super-Mario-3D-Land-SGE)
  - *Used for partially unlocking a save file in order to compare RAM dumps.*
- [SM3DL Shiny Star Fix](https://gbatemp.net/threads/how-to-get-5-sparkly-stars-savefile-back-on-super-mario-3d-land.542645/)
  - *Consulted for information/findings about converting a non shiny (1->5) star save to a shiny (1->5) save.<br />Thanks a bunch!*
- [Super Mario Wiki](https://www.mariowiki.com/Mystery_Box)
  - *Among other resources, consulted for information about f.e. Mystery Boxes.*
- [Gateway Cheat Codes Guide](https://gbatemp.net/threads/guide-how-to-create-gateway-cheat-codes.410926/)
  - *Among other resources, consulted as a quick cheat sheet in case I forgot or <br />wanted to double check a certain code type.*
- [GSH Guide](http://viper.shadowflareindustries.com/?file=hackv500c.html&cat=hax0r#hax0r_mj)
  - *Among other resources, consulted for information about how to search addresses/values for f.e. a Moon Jump code.*

### Credits
- I searched/created (almost) all codes myself
  - *by using the above software/tools and RAM Dump comparisons &*
  - *by doing quite a bit of research, digging and testing.*
- **Codes from other cheat contributors** that I reused, renamed, optimized and converted to an all region version:
  - Always Tail Attack (Any Powerup)
  	- *Original Action Replay code by [nolberto82](https://www.max-cheats.com/view.php?ItemID=531).*
  	- *Converted to GS (based on findings by [buzzmaster1980](https://www.maxconsole.com/threads/help-with-super-mario-3d-land-aree.54363/)), optimized (ability to restore default when not in level) & converted to All-Region by me.*
  - Always Flutter (Any Powerup)
  	- *Original Action Replay code by [nolberto82](https://www.max-cheats.com/view.php?ItemID=531).*
	- *Converted to GS by [buzzmaster1980](https://www.maxconsole.com/threads/help-with-super-mario-3d-land-aree.54363/).*
  	- *Optimized (ability to restore default when not in level) & converted to All-Region by me.*
  - Infinite Time
  	- *Original code by [optantic](https://github.com/JourneyOver/CTRPF-AR-CHEAT-CODES/blob/master/Cheats/Super%20Mario%203D%20Land%20(EUR)/0004000000053F00.txt).*
  	- *Optimized (ability to restore default when not in level) & converted to All-Region by me.*

### Developer Notes
I added my [developer notes](https://github.com/KimDebroye/N3DS-Cheat-Codes/blob/master/Super%20Mario%203D%20Land/_DevNotes/SM3DL_DevNotes.txt) to this repository for those interested in reading about how these codes came to be.

### Personal Notes
I did this out of pure fun and interest to find out about how a cheating process works, not necessarily to play a game.
It has been a fun ride finding and creating cheat codes for this game.
I sincerely hope you all like toying with the game using the cheats provided
and that it may reflect a bit of the joy I had tinkering with them.
