# Project: Ordinator Implementation
Right now we have a fantastic interface to allow new skyrim players to easily customize their characters in game... but we can do better.  The Skyrim modification <i>Ordinator - Perks of Skyrim</i> is a mod that completely overhauls the perk system.  And with an active community, 22862 endorsments, and at over 1,387,000 downloads (as of 1/9/2018), it has come to our attention that we should be extending our utility to these users as well.

#### What is Ordinator?
Ordinator overhauls the perk trees of Skyrim, replacing them with ~400 new perks to improve the depth and fun of building and playing your character. It accomplishes this in a lightweight, compatible and clean fashion.

Here's a screenshot of just a few perk trees we will be implementing:  
![Enchanting, Heavy Armor, Illusion](https://staticdelivery.nexusmods.com/mods/1704/images/1137-0-1492367685.png "Perk Tree Overhaul")

#### Whats the progress on the project?
You can view our progress [HERE](https://github.com/aaronmaynard/Skyrim-Perk-Utility/projects/1).  When we are done, it will look a little something like this:
![Example](https://raw.githubusercontent.com/aaronmaynard/Skyrim-Perk-Utility/master/project/ordinator_implementation/resource%20images/example.jpg "Speech perk tree with Ordinator Mod")

#### How can I contribute?
-  Comment in the issue that you would like to do it.
-  Open the [Skyrim-Perk-Utility](https://github.com/aaronmaynard/Skyrim-Perk-Utility) GitHub page and click the ★ Star and then ⑂ Fork buttons.
-  Work inside the project folder [Skyrim-Perk-Utility/project/ordinator_implementation](Skyrim-Perk-Utility/project/ordinator_implementation)
-  Once you've made sure all your changes work correctly and committed all your changes,
-  Visit your fork on GitHub.com (https://github.com/YOUR-USER-NAME/Skyrim-Perk-Utility) and create a pull request for your changes.
-  Make sure your pull request describes exactly what you changed and references this issue (include the issue number in the title like this: #3)
-  Please do not fix more than one issue at a time. Your pull request should only fix what is described in the issue.

#### Where can I learn more about this mod?
You can visit the mod page on [Nexus Mods](https://www.nexusmods.com/skyrimspecialedition/mods/1137?). Let them know what we're working on!
:medal:

## Progress Summary
If all items have been checked, the perk will be written off.  

| Perk            | Added to .js | Detailed | Nodes Mapped | ID Ready |
| :---            |    :---:     |   :---:  |     :---:    |   :---:  |
| ~~Some_Perk~~   |      ✔️      |    ✔️    |     ✔️      |    ✔️    |
|   Alchemy       |              |          |              |          |
|   Alteration    |              |          |              |          |
|   Archery       |              |          |              |          |
|   Block         |              |          |              |          |
|   Conjuring     |              |          |              |          |
|   Destruction   |              |          |              |          |
|   Enchanting    |      ✔️      |    ✔️    |              |          |
|   Heavy Armor   |      ✔️      |    ✔️    |              |          |
|   Illusion      |      ✔️      |    ✔️    |              |    ✔️    |
|   Light Armor   |      ✔️      |    ✔️    |              |          |
|   Lockpicking   |      ✔️      |    ✔️    |              |          |
|   One-Handed    |      ✔️      |          |              |          |
|   Pickpocket    |      ✔️      |          |              |          |
|   Restoration   |      ✔️      |          |              |          |
|   Smithing      |      ✔️      |          |              |          |
|   Sneak         |      ✔️      |          |     ✔️       |          |
|   Speech        |      ✔️      |    ✔️    |     ✔️       |          |
|   Two-Handed    |      ✔️      |          |     ✔️       |          |


## Note about Perk ID's
Because we cannot tell where you have installed Ordinator in your load order, we cannot give you the full ID to run your script. What we <i>have</i> done is make is as easy as possible for you to run the script that fits your load order. You will notice that some perk ID's look like this `__0148FE`, this means that the ID will change depending on your load order.  You can tell which values will replace the beginning portion of the ID's by viewing your load order. For example: 

![loadorder](https://i.imgur.com/2wf3l7H.png)

In this image you can see that the Whistling Mine.esp has load order ID of `15`, this is <b style="color:red;">not</b> the 15th mod in the load order! The easiest way to find your load order if you are not aware how hex counting works is using a mod manager such as Nexus.  If you prefer to use the in game load order, you can use this image as a reference as to what your mod may be.  In the documents you download, you can `CTRL+F` on PC, `CONTROL+F` on Mac, and replace the two underscores `__blabla` with your load order `06blabla` id.
