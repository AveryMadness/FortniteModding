# Quick tutorial on how to mod older versions of Fortnite.

## 1. Download the UE4 build that the Fortnite version you want to mod uses. 

- (For Season 4 i recommend using 4.19 as custom maps work on it, and for season 7, 4.21.)

> How to check what UE4 build the Fortnite version i want to mod uses?

![It is easy.](https://cdn.discordapp.com/attachments/873974318101565440/894271829957554176/ezgif-3-c813ffde612b.gif "")

## 2. After you download Unreal Engine, open it and create a new blank project called "FortniteGame".

## 3. After you've done that, make a folder and call it "Maps", then create a level inside of it and choose a name for it.
![Hi](https://cdn.discordapp.com/attachments/874274681316864028/894277073173086258/ezgif-3-918f36ef43eb.gif "")

## 4. Then create 2 c++ classes, one that's an Actor, call it "FortTimeOfDayManager", and second one thats a child of WorldSettings, call it "FortWorldSettings".
- You need either Visual Studio 2017 or 2019, depends on the UE4 build that you are using!

![Hi](https://cdn.discordapp.com/attachments/894281085393977408/894281159985471498/ezgif-3-c9251f59b54b.gif "")

- If you have this issue, press Yes
![Hi](https://media.discordapp.net/attachments/874274681316864028/894284910582464512/unknown.png "")
- It will open the output log window, you possibly dont have Windows SDK v8.1 installed! If thats the case then install it and.
![Hi](https://media.discordapp.net/attachments/874274681316864028/894284641392021514/unknown.png "")

## 5. After creating the c++ classes, in visual studio go to FortWorldSettings.h, add an include for FortTimeOfDayManager, and paste the rest under "GENERATED_BODY()"
**#include "FortTimeOfDayManager.h**
 
**public:**

 ![Hi]( https://media.discordapp.net/attachments/894281085393977408/894287035383283712/unknown.png "")
 - You need to rewrite this part because markdown is skunked.
