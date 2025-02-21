<h1>Inventory App - Pablo Guardia</h1>

================================

Inventory App created for Assignment 6 of COP4656 - Mobile Programming.
The app's code follows the two codelabs for Unit 6, Pathway 2 of the Android Basics with Compose course. It displays a screen with a list of items in a database, each item containing a name, a price, and an amount in stock. Tapping on an item allows further information, the ability to sell it one by one, the ability to delete it, and finally the ability to edit all fields as one sees fit. Finally, there is a button on the homepage to add a new item to the database. The app works with the Room abstraction layer for SQLite, meaning that the database must persist between runs and no data should be lost in between runs.

================================

<h3>Update (February 20th, approx. 7:00 P.M.):</h3>

- Modified README.md file to usual format

<h3>Update (February 20th, approx. 7:45 P.M.):</h3>

- Completed "Persist data with Room" section of pathway
- Updated README.md file

<h3> Update (February 21st, approx. 1:00 A.M.):</h3>

- Fixed an issue where app would crash whenever the user would try to add a new item.
	- The function getDatabase() in InventoryDatabase.kt contained a .fallbackToDestructiveMigration() line, which prompted the crash. Removing this line fixed the issue
- Updated README.md file

<h3> Update (February 21st, approx. 5:30 P.M.):</h3>

- Completed "Read and update data with Room" section of pathway
- Updated README.md file
