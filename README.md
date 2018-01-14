# (Classic Word Games NDS/DSi Exploit)
<img src="https://cdn.discordapp.com/attachments/368785644173918210/401850045642833921/JPEG_20180113_162731.jpg" width="320">
A successful attempt to exploit the game Classic Word Games for the Nintendo DS/Nintendo DSi to execute unsigned code from the savegame.

* Runs in TWL/DSi-mode if you use a retail cartridge of the game on a DSi or 3DS system. Otherwise, it runs in NTR/DS-mode regardless.
###
As included in the repo, you'll be able to get your DSi's CID for things such as downgrading (via hardmod). To be able to run that payload specifically, navigate to the `/Exploit/CID_CWG_savesploit` directory and choose the appropriate savefile that suits your region.
###
## Usage (Patching the savefile)
* Win32: `classicfix savegame.sav`
* Linux: `./classicfix savegame.sav` (You'll need to compile the `classicfix.c` before using it. You can also use WINE as well)
###
## Triggering the exploit
Click "Select a Profile" on the main menu and BOOM!
###
## Special thanks to:
* jerbear64 (testing the exploits on retail for US/EUR users)
* wintermute (calculation code)
* zoogie (Original CID-Dumper code)
* CTurt (Giving helpful advise on payloads for TWL-carts)
###
## Support:
* Supports both US & EUR versions of the game.
* Works with emulators. (desmume, no$gba, etc.)

###
## Requirements:
* A copy of the "Classic Word Games" DSi-Enhanced game. (Cartridge specifically)
* Any DS that's in the DS family. (The DS family and the 3DS family will not be able to print a valid DSi CID because the CID payload is specifically for the DSi.)
* A way to inject the save. (Use TWLSaveTool on the 3DS, you'll need CFW on your 3DS. GodMode9 is an option as well)
