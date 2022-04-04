# nso-place tool
Needy Streamer Overdose /r/place repo to store the template and script for outlining the place to put titles 



## HOW TO USE THE TEMPLATE AND SCRIPT ON /r/place
Our friends at r/osuplace have made an overlay script! Use this to make sure you're placing pixels in the right spot.

### Extension (Step 1: Download)

USE THIS FOR CHROME/OPERA
[https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en]

USE THIS FOR FIREFOX
[https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/]

### Userscript (Step 2: Install)

Install/click [userscript.user.js](https://github.com/Seija-Kijin/nso-place/raw/main/userscript.user.js) from this repository to the addons listed above.

### Running (Step 3: Place!)

Head back to r/place, and do a hard refresh (ctrl+shift+r / ctrl+f5). You should see something like this if it's working:
![image](https://user-images.githubusercontent.com/13429544/161412869-e1ae8ed2-77cf-4592-b8d6-48ef5fa1e3ec.png)

*The small squares are the intended color. Hover over them and select the right color, then place!*

## Meta

This script & repo are cloned from [Anticept/httyd-place](https://github.com/anticept/httyd-place) to allow multiple people to be able to update a template image.

To edit the template:

Edit the [onepiece_full.png](onepiece_full.png) file without changing the pixel dimensions. Then run the [dithering.py](dithering.py) script on the image. PR:

* YOUR EDITED onepiece_full.png
* the output onepiece_template.png

Merge it!
