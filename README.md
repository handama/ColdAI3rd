# ColdAI3rd
[中文](README_zh.md)

To Gamers
---------

Welcome to Cold AI 3rd! From its name, you've already known that this is the third edition of Cold AI. However, unlike the previous two versions, this version is built entirely from scratch, which could avoid the interference of the existing AI scripts and fully control the behavior of AI. Nevertheless, the third edition still retains some features of the previous versions of Cold AI, such as rhino tank rush, war miner rush, harassing miners, iron curtain terror drones, and so on.

To use this AI, you need to prepare a 1.001 version of Command & Conquer: Yuri's Revenge (the version can be seen in the lower right corner of the main menu of the game), and copy all the contents in this compressed package (or folder) to Yuri's Revenge folder (if you've copied them correctly, this file should be in the same directory as gamemd.exe). Then run RunColdAI.bat to start Cold AI. All files in this compressed package have their particular function and should not be deleted unless you know what you are doing. Considering that there are some obstacles to run Yuri's Revenge in contemporary operating systems, this AI comes with cnc-ddraw. If the program cannot work or you want to adjust the display settings, you can open "cnc-ddraw config.exe" to adjust.

Cold AI 3rd has hardly changed any original unit. For the comfort of players, this AI enables the "automatic repair" function by default. To disable it, simply delete AutoRepair.ini.

Due to some strange triggers in the first mission of the Allied campaign in Yuri's Revenge, this mission could not be cleared when using this AI. In addition, this AI does not guarantee compatibility with any other mods, maps, or missions. The author guarantees that this AI does not contain any code that damages the computer system, , and the author is not responsible for any consequences arising from the use of this AI.


To mod developers
---------

Cold AI 3rd hardly modified the original rulesmd.ini file, only uses the [#include] function of Ares at the beginning. Therefore, this AI is very friendly to mod development based on it. It should be noted that the new buildings used in this AI follow the original [buildingtypes] registration, and many AI scripts containing this registry order are used. Therefore, your mod should not register or modify the order or actual function of any building with an order less than or equal to 423 (for example, you should always ensure that building 11 is the Battle Lab of the second side).

Aimd.ini of Cold AI 3rd is only used to register [#include], so you can even merge the contents of this file directly into your aimd.ini. However, the author suggests developing your AI completely based on this AI.

Artmd.ini of Cold AI 3rd only fixes the fire animation of Apocalypse Tank and adds some codes used in the author's other maps compared with the original file to increase compatibility with the author's other works. Therefore, you can delete the artmd.ini file, continue to use your existing file.

The author will not answer any questions in the customization, nor will he be responsible for any questions arising therefrom.

Cold AI 3rd uses an MIT license, which means you can use it in your mods, maps, or any other works at will without the consent of the author. However, you must include license_coldai3rd.txt (located in .\licenses\) in the distribution of your work. It should be noted that although the MIT license allows the software to be applied to commercial software, EA clearly stated that Command & Conquer Modding is "Not for commercial profit". Therefore, although the attempts to include this AI in commercial software will not infringe the rights of the author, it will still infringe the rights of EA.


Copyright notices
---------

Cold AI 3rd uses additional library files or software, which are:

*Ares (https://ares.strategy-x.com/)

*Phobos (https://github.com/Phobos-developers/Phobos)

*cnc-ddraw (https://github.com/CnCNet/cnc-ddraw)

The licenses of relevant software are included in .\licenses\ directory.

                                               Handama

                                          18th January 2022
