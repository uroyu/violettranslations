This is the repository for simplifying the translation process for games and locations on our site, as well as making the already made translations more accessible

Site UI translations are in /gamepage/lang
Game location translations are in /locations

To make a UI translation, download sitetemplate.json and fill out the first three lines.

The first line should have the two letter code for the language. 
The second line should have the language name, in the language that it is for, example being Español (correct) instead of Spanish (incorrect)
The third line is for right to left formatting. This should usually stay false besides specific languages.

Then, replace all the strings below with the translation for your language which you are translating (Make sure to only edit the text on the right, which shows up blue in VS Code)

Once you have translated all the text, rename the file to your two letter language code from before (example: en.json)
Then. make a pull request to this repository (file should be in /gamepage/lang/ or send it to me on discord at "violetsitas".
