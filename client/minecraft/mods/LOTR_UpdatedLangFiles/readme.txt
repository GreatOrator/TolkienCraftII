LOTR lang file update-helper

This helper system is to assist people in updating the mod's lang files after a mod update.
To enable the helper, go to the mod's config file - or ingame config menu - and set 'Run language update helper' to 'true'.

When the mod is loaded, it checks all lang files in the mod zip file against en_US.lang, and outputs a copy of them here.
If a lang file is missing any keys (names of new blocks, items, etc. added in an update) then those keys are added to the copy here.
Unused keys are also removed - for example, if a feature is removed from the mod, or a key is renamed.
The lang files outputted here also have their contents ordered in the same order as en_US.lang, to make comparisons easier.

The mod's current en_US.lang is also outputted here for convenience.

I hope this system will be much easier than checking a lang file against en_US.lang, for every update, to find out what has been added.

DO NOT STORE ANYTHING in this folder! This folder, and its contents, are re-created every time the mod loads.
Anything in the folder will be deleted.
If you want to update one of the lang files, copy and paste it somewhere safe!

And finally, if you have updated a lang file (or created a new one), the best way to send it to us is through the mod's Facebook page.
We credit everyone by name in the mod's credits file unless asked not to. If you do not want your name listed, then please say so.

Please note: Lang files must be in UTF-8 format, otherwise errors will occur.
