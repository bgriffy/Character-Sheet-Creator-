**Note: Since this application was created for a school project, I am not allowed to make the code public in accordance with university policy. This is to prevent other college students from plagarizing. But, for prospective employers, I would be more than happy to send you the code personally.

# D&D Character Utilities

## Description
D&D Character Utilities is a tool meant to help dungeon masters as well as regular players manage some of the more tedious parts of roleplaying adventures. While this project is mainly geared towards Dungeons and Dragons, it can be used to enhance any roleplaying game.

# How To Use
All commands should be run from the project root directory.
1. Install all dependencies with `python3 setup.py install`
2. Run the application with `cd src && python3 dnd_tools.py`.

## Components

**Character Managment**
- *Create character sheets*
  -  One of the biggest struggles of any roleplaying game is having to lug around binders containing sheets of information about each character. But, with digital character sheets, this tedious endeavor is a thing of the past! You can now save your strength for the adventures that lie ahead instead of spending it all carrying that mammoth binder.
- Store character sheets locally  
  -  Not only are character-sheet binders cumbersome, but if they get lost or destroyed, then you could lose important information. The Character Management tool solves this problem by allowing you to store your digital character sheets. This way, your characters legacy will survive the test of time.
- Update values to character sheets as needed
  - Time ravages and changes all things, and our roleplaying characters are no exception. Luckily, the Character Managment tool makes this task a breeze! Feel free to edit a previously-created character sheet with this feature to reflect how your character changes during the course of an adventure.
- Import/Export
  - Sharing character information with fellow players is an essential part to any roleplaying game. The import/export feature allows players to share their digital character sheets with each other so that everyone is on the same page.

![alt text](https://cdn.discordapp.com/attachments/520161015594483715/520163966715035648/Screenshot_from_2018-12-06_04-05-26.png)

**Scenario Generation**
- Randomized NPC
  - NPCs add depth to roleplaying adventures. But, sometimes being able to consistently create unique and interesting NPCs is challenging for a DM. Within our scenario generation tool, you can quickly generate enemy or friendly NPCs by simply choosing a difficulty level. The application will tell you the name, title, and location of the NPC.   
- Randomized Monster
  - Monster fights have never been more fun! With this feature, you can quickly generate a monster (or a group of monsters) based on a specified difficulty level. This feature will also generate the setting for the fight.   
- Randomized item
  -  Similar to the monster and NPC generation features, this tool allows you to generate items for different scenarios. You just need specify the difficulty, and voila! You have yourself a unique item that you can do whatever you want with.    
- Randomized stats
  -  This feature allows gives you the option to generate random stats which you can use as you wish.
- Randomized scenario
  -  With this feature, you can generate a scenario for you and your party. A scenario can be generated using a specified difficulty and a randomized item, NPC, or monster. The possibilities are endless!

![alt text](https://media.discordapp.net/attachments/520161015594483715/520161119038341131/Screenshot_from_2018-12-06_03-49-29.png?width=720&height=520)

**Dice-Roller**
- Are you tired of forgetting your dice set and having to ask one of your fellow players to borrow theirs? Or maybe you just don't feel like doing any kind of math. Well rest easy, because the dice-rolling tool gives you all the functionality of a complete set of dice. You can roll any number of 4, 6, 8, 10, 12, and 20 sided dice.  And not only will this tool show you the results of an individual roll, but it will also show the sum of dice rolled at the same time. Your dice roll history will also be displayed so that you do not have to worry about writing anything down. The average of all your rolls will be displayed as well.  

![alt text](https://cdn.discordapp.com/attachments/520161015594483715/520163230505762836/Screenshot_from_2018-12-06_04-02-28.png)

**Spell Book**
- To further lighten the load that the roleplayer needs to carry, this tool allows you to store spells digitally. Gone are the days of searching through spell pages to find out what spell does. With this feature, you can create spells, assign attributes to them, delete spells, and search up different spells in case you forget what they do.  

![alt text](https://cdn.discordapp.com/attachments/520161015594483715/520166845739958272/Screenshot_from_2018-12-06_04-16-51.png)

## Libraries
- **Names**: Used for scenario NPC generation.
- **PyQt**: Used for the GUI.
- **SQLAlchemy**: Used to interact with an SQLite database.
- **CSV**: Used to import/export character sheets.

## Other Resources
- **Qt Designer**: Used to design the user-interface.

## Work Distribution
Each member of the group had his hand in various aspects of the project,  but here is a general breakdown of what each member worked on:
- **Joshua Freedman** – Local Storage Organization, Character Sheets, Character Importer/Exporter
- **Brent Griffin** – Spell Book, Character Importer, Text and Scenario Generation
- **Dexter Ketchum** – Text and Scenario Generation, Dice Rolling Tools
- **Lance Newman** – Dice Rolling Tools, Character Exporter, Unit Testing
