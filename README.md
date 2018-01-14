# (Classic Word Games NDS/DSi Exploit)
<img src="https://cdn.discordapp.com/attachments/368785644173918210/401850045642833921/JPEG_20180113_162731.jpg" width="320">
A successful attempt to exploit the game Classic Word Games for the Nintendo DS/Nintendo DSi to execute unsigned code from the savegame.

Runs in TWL/DSi-mode if you use a retail cartridge of the game on a DSi or 3DS system. Otherwise, it runs in NTR/DS-mode regardless.
###
As included in the repo, you'll be able to get your DSi's CID for things such as downgrading (via hardmod). To be able to run that payload specifically, pick the `/Exploit/CID_CWG_savesploit` and choose the appropriate region.
###
## Usage (Patching the savefile)
* Win32: `classicfix savegame.sav`
* Linux: `./classicfix savegame.sav`
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
* Supports both US or EUR versions of the game.
