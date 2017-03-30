# LuaRio_Bot
LuaRio Bot is Bot Created for Super Mario Bros in Lua for FCEUX Emulator.
This bot will also work for SMB2 (J) aka SMB Lost Levels. (Tested).

Note : This is still in beta in its earlier stages it can be improved more. So it might get stuck in some places where Enemy is inside walls and bot cannot clear until all enemies are dead. and some Piranha plants are still present in enemy slot so bot thinks it still alive and cannot move until its removed from that slot.

FAQ :

Q : How to Run this Bot ?
A : Open FCEUX Emulator and open Super Mario Bros ROM file.
then go to FILE > Lua > New Lua Script Window > Browse > Then Select LuaRio_Bot.lua > Then Click Run and Enjoy :)

Q : How this Bot Works ?
A : LuaRio Bot Works by Calculating Enemy and Player Distance and from this it know if enemy is close enough to kill it. And it also uses Object Detection with Pipe or Block and from this it knows where to jump or do frame perfect input .
Bot will not move forward until all enemies are killed . It Checks this enemy and object detection about every 2-4 Frames so it knows about all the enemies present in current page and is capable of killing them all.
Unfortunately it doesn't know where are pits and it may fall in pits some times.

Q : Does this Bot Plays same everytime for same level ?
A : Probably yes, But sometimes there is different Pattern of Enemy Like Hammer Bro Now are at different Positions so it might change its inputs accordingly.

Q : Can it take All Power up ?
A : This is still in beta, and currently it can only take Mushroom . 

Q : Can it Play All Stages ?
A : Yes, Almost all even water stages . But Stages which have huge pits and gap between ledges it cant play those stages .
Like for ex : 1-3 , 3-3 , 4-3 , 5-3 , 6-3 levels.
