# translation
Contains the crowd sourced translations for VoxelGamesLib

THE FILES IN THIS REPO ARE GENERATED AUTOMATICALLY, PLEASE DO NOT OPEN PULL REQUESTS HERE BUT USE POEDITOR TO CHANGE THE TRANSLATIONS!

### How To Translate
Translations for VoxelGamesLib are handeled via properties files. Luckly we use a nice website to translate stuff, so you don't need to fiddle with the files itself (that doesn't mean you can't do that for your own server).  
You can find the project here https://poeditor.com/join/project/taIPnsW7Pe, it should be pretty self explanitory. Please note that after signing up I get an email where I need to confirm you as contributor, mostly to avoid spam. So please give me up to 24h to respond (if I am too slow, feel free to open an issue here to that you don't get lost)   


### Variables
VGL has simple variables that need to be used in translated strings.  
For example `COMMAND_NO_PERMISSION` offers the variable `role` which will be replaced with the role needed to run that command. The english translation for this key looks like this `{red}You need to be {yellow}{role}{red} to execute this command!`. The variable can be placed everywhere in the string, but it has to be there exactly one time.  
As you can see, there are also color variables available. You just write the standard minecraft color names and VGL will handle all formatting needed.
