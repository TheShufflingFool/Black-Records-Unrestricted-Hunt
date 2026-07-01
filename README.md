# Black Records Unrestricted Hunt (B.R.U.H.)

A mod for The Legend of Heroes: Trails of Cold Steel II that removes the New Game+ requirement for all the events related to the Black Records.
Tested on XSEED PC version of the game.

Best paired with [B.E.S.T.](https://github.com/TheShufflingFool/Basically-Extra-Social-Time) for unlimited bonding points.

## What even are the Black Records?
To put it in a spoilerless manner - they're a series of books containing some interesting lore. The quest, which involves locating them and decoding their contents, spans the entire game - from the beginning of Act 1 to the Epilogue - despite never appearing in the Notebook. Furthermore, the Black Records storyline ends with a **VERY** important cutscene, which the next game assumes the player has seen (likely due to lack of a save import feature).

## Installation
**IMPORTANT!** This mod only works with the text language set to English. The voiceover language is irrelevant.

### RECOMMENDED METHOD
1. Download the latest release of AdmiralCurtiss' [SenPatcher](https://github.com/AdmiralCurtiss/SenPatcher) and use it to patch your game.
2. Download the latest release of `BlackRecords_Unrestricted.p3a` ([here](https://github.com/TheShufflingFool/Black-Records-Unrestricted-Hunt/releases/latest)).
3. Locate the game's main directory:
   * for Steam version, right-click on `The Legend of Heroes: Trails of Cold Steel II` and select Manage → Browse local files
   * for GOG version, right-click on `The Legend of Heroes: Trails of Cold Steel II` and select Manage installation → Show folder
4. Locate the `mods` folder. If it can't be found, start and quit the game.
5. Move or copy `BlackRecords_Unrestricted.p3a` to the `mods` folder.
6. To uninstall, delete `BlackRecords_Unrestricted.p3a` from the `mods` folder.

### UNSUPPORTED METHOD
If, for some reason, you can't or don't want to use SenPatcher, follow these steps:
1. Go to the latest release ([here](https://github.com/TheShufflingFool/Black-Records-Unrestricted-Hunt/releases/latest)) and download `Source code (zip)`.
2. Locate the game's main directory:
   * for Steam version, right-click on `The Legend of Heroes: Trails of Cold Steel II` and select Manage → Browse local files
   * for GOG version, right-click on `The Legend of Heroes: Trails of Cold Steel II` and select Manage installation → Show folder
3. Open the downloaded file and extract the `data` folder into the game's main directory (you can just drag and drop or copy and paste).
4. When prompted to merge folders and replace files, accept all changes.
5. To uninstall, verify integrity of game's files.

## FAQ
* **How do I know I installed the mod correctly?**  
  <ins>RECOMMENDED METHOD ONLY</ins>: You should see a new line regarding modded files in the main menu in the bottom right corner (or, if you have other mods and it was already there, the number of modded files should change). If it doesn't appear (or the number doesn't change), make sure you downloaded the correct file (you want the .p3a one, not any of the archives) and placed it inside the correct folder.
  <img width="1280" height="720" alt="bruh_installed" src="https://github.com/user-attachments/assets/6bc3aa58-ae1d-4d05-86aa-02d734efccfe" />
  If you use other mods and the books don't appear, it's highly likely there is a compatibility issue. You can try editing `order.txt` inside the `mods` folder and moving `BlackRecords_Unrestricted.p3a` to the top of the list. That should unlock the Black Records but might override changes from the other mods.

  Lastly, do not worry if Black Records 1 is not the first book you find - they're given out of order, unlike the in-game novels.

* **Why should I use this mod? Isn't NG+ just better?**  
  This mod's goal is simple - to offer a vanilla New Game experience without leaving out important story elements. NG+, even with no carry overs, changes certain aspects of the game - disabled tutorials, some extra items in certain shops (like the Zemurian Ore) or larger fish pools, to name a few. If you don't care about an occasional spoiler or two, feel free to use someone's Clear Data save instead.
  
  Check the [table at the bottom](#bruh-vs-new-game) for a list of differences (contains some minor spoilers).

* **I'm in the middle of my playthrough. Do I have to start a new game to use the mod?**  
  No, it can be installed at any point before commencing the final operation, which is the deadline for giving all the Black Records to a certain someone. However, most of these books can only be found at very specific points in time. If you're past such point, or have missed a book, they can be purchased as curios, but it will cost you a lot - a full set is around 150k mira.
  
* **Can I get the achievement tied to this questline if I use the mod?**  
  Yes, the achievement is unlocked upon watching the final cutscene. While I haven't tested this personally, I've received several confirmations from other people.
  
* **Will this work on Steam Deck?**  
  As far as I know, yes. I don't own one so I can't test it myself but, seeing that other mods work on it, I don't see why this one wouldn't.
  
* **What's with the silly name?**  
  It's the only appropriate reaction to learning that a crucial piece of information, directly referenced in the next game, is locked behind New Game+. As Randy would say:

  ![bruh](https://i.imgur.com/maj4ocb.png)

## B.R.U.H. vs New Game+
| | New Game with B.R.U.H. | New Game+ |
| ------------- | ------------- | ------------- |
| **Black Records** | fully available | fully available |
| **bonding points** | limited (unlimited with [B.E.S.T.](https://github.com/TheShufflingFool/Basically-Extra-Social-Time)) | unlimited |
| **tutorials** | appear during gameplay upon unlocking new features | don't appear during gameplay, unlocked in the Notebook from the start, including some with spoilers |
| **fishing spots** | unaffected | contain late-game fish |
| **extra items in shops** | no | yes |
| **extra boss in the Finale** | no | yes |
| **spoiler message in the Divertissement** | no | yes |
| **Epilogue's Mirror cutscenes** | no | yes |
