# Pokemon GO Assets

Repository of all mined assets, including sprites, sounds, and news items. This repo is organized based on category and is a combination of downloaded/remote assets and assets found inside the APK.

## Folder Structure

### Images

All 2D images of all assets that we mine are located here. Assets are organized based on the category, such as `Pokemon`, `Items`, `Backgrounds`, etc.

### 3D Assets

All 3D models and their textures (if present) of all assets that we mine are located here. Assets are organized based on the category, such as `Pokemon`, `Items`, `Clothing`, etc.

### Sounds

All sound effects and music that are mined are found here. They are organized by category such as `Pokemon Moves`, `Music`, `Menu Sounds`, etc.

### Texts

Mined text assets which contain quests among other things will be found here. Inside there are two folders, one for `Latest APK` and one for `Latest Remote`. When Niantic pushes a text update, it's pushed to the Remote. Once a new APK is released, all remote pushes are merged into the APK and removed from the Remote; therefore, we maintain both.

**Note:** Keep in mind it is expected that the Remote will have items removed from it after a new APK is released.

### News

All datamined news images and texts from the In-Game News will be found here. There will be two folders: one for images and one for texts. In Texts, the file called `CurrentNews.tsv` will contain the most recent news file and the `Old News Texts` will contain a history of older news texts. Keep in mind each tsv contains all current news in the game.

### Shop Images

Any images that are displayed in the shop that we datamine.

### Photobombs

Images that appear as a photobombed overlay during Snapshots will be in this folder. There is no back catalog as images can only be pulled during their event window.

### Quest Branching

Any images that appear during quest branches (the banners or the chosen images themselves). They are broken up into their quest/event folders.

### Mega Portraits

The images the game uses to display a mega behind a Mega evolved Pokemon.

### Candy Color Data

The JSON structure that the game uses to generate the in-game candy colors.

## Disclaimer

This repo is for educational use only. All content within this repo is the property of The Pokemon Company and Niantic. PokeMiners did not create or modify any images or sounds found within this repo, and all copyright belongs to the respective companies. Please respect the original source material.
