# Word Master Localization Template

This is a template to help localize [Word Master](https://github.com/octokatherine/word-master/) which is based on [Wordle](https://www.powerlanguage.co.uk/wordle/). The original Word Master game is [here](https://octokatherine.github.io/word-master/).

Edit the file `wordbank.txt` to change the list of acceptable 5-letter words, and edit `keyboard.txt` to change which characters are available (and where they appear on the on-screen keyboard).

Go to "Settings," "Pages," and ensure the source is set to "Branch: gh-pages" "Folder: / (root)". After that it hopefully will build and deploy automatically. The URL is based on your username and the repo name. For example, if your fork of this repo is hosted at `https://github.com/walt-jabsco/word-master-ska`, then the game would be live at the URL `https://walt-jabsco.github.io/word-master-ska`.

This is very very very much still in-progress! You can't put in digraphs, or use right-to-left scripts, and the code is very brittle.