This is a fork of Novetus_Src that can be rebuilt easily and be functional. I have enabled 'AdminMode' to allow you to be able to make modified clients without it getting angry at you.

To rebuild a modified version, you'll need to open it in Visual Studio 2022, restore Nuget packages, and build it. Once built, navigate to the 'admin_mode' folder, and replace corresponding build files. Do not delete the 'data' folder and overwrite it, rather you will need to replace what is built in the data folder in the source build, because the data folder in the 'admin_mode' folder contains additional necessary files.

I was able to assemble the fork using https://bitl.itch.io/novetus and getting the necessary files from the 'snapshot' download available.