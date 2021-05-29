# freetube-nord
### Brief Overview
 A third party theme for the FreeTube YouTube Client that is based on the [Nord Color Palette](https://www.nordtheme.com/)
### Screenshots:
![picture alt](https://raw.githubusercontent.com/makorino/freetube-nord/main/screenshots/sc1.png)
![picture alt](https://raw.githubusercontent.com/makorino/freetube-nord/main/screenshots/sc2.png)
### Pre-requisites:
1. 7-Zip
2. Asar7z Plugin (can be found [here](https://www.tc4shell.com/en/7zip/asar/))
3. FreeTube Desktop Client
### How to Install:
1. Install the Asar7z plugin for 7-Zip
2. Navigate to the directory where you installed the FreeTube Desktop Client
3. Navigate to resources
4. Right-click on the "app.asar" file, hover on 7-Zip, then click on "Open Archive"
5. Once the archive has opened, in 7-Zip, open the "dist" folder
6. Look for the "renderer.03bb8a88ac505c91fa35.css", then delete it
   6.1. If you're using FreeTube version 0.13.0 beta, the file you have to delete is "renderer.f4905516da6654a1c9e9.css"
8. Replace it with the file of the same name from this repo
9. Open FreeTube, then go to Settings
10. Scroll down to "Theme Settings", then change into the following parameters:
   1. Base Theme: Black
   2. Main Color Theme: Cyan
   3. Secondary Color Theme: Cyan
11. If all works correctly, then you should have applied the Nord theme by now. Enjoy!
