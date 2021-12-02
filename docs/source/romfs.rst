Understanding ROMFS & EXEFS
===========================
This explanation goes over the technical aspects of these two folders, **Not** how to obtain them. If you wish to figure out how to obtain them, click here for our dumping guide.

ROMFS
-----
The ROMFS stands for Rom Filesystem which is a pretty generic and broad term, because wouldn't *everything* in the game be apart of it then?
This definition and the context that ROMFS is in doesn't mean a game rom. It means **Read Only Memory** Filesystem which definitely clears things up.
Inside this folder you will find all the assets for the game, this includes data,models,maps etc. Everything that is streamed and then Read, The game pulls from here.
This is where the grand majority of edits like changing a creatures typing or changing the accuracy of a move would take place.

EXEFS
-----
The EXEFS stands for Executable Filesystem which is a bit more descriptive than the previous one. This means the files or code that is ran in the background, at startup, during specific operations (like in Battles) gets stored somewhere in here. The files in the Executable Filesystem will be your more complicated ones as this is where the foundational code that the game is built on is stored.

A example of a EXEFS modifcation would be something like a No EXP Share Modification, which changes a foundamental codes operation.



How it comes together
---------------------
In order to really describe and have this make sense to you, I will be using a **pizza analogy**.

Imagine the EXEFS as the dough to a pizza, the pizza dough is the foundation in which the sauce, cheese and toppings lie on top of.

The toppings are the contents of the ROMFS, the sauce, cheese, pepperoni & other toppings.

Together they layer up to create a final product, just like a pizza does!



