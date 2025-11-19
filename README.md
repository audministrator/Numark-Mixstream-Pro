# Numark-Mixstream-Pro
This repo holds the  **Numark Mixstream Pro & Pro GO** controller mapping. \
Here you can find the documentation : 
https://github.com/audministrator/Numark-Mixstream-Pro/wiki/Numark-Mixstream-Pro-Documentation


**Refactoring and fixes:** N/A

**Features:** Includes Vinyl brake option, Hotcues, Saved Loops, Auto Loop, Roll Loop, Beat loop (8-1/2 beats), jogWheel, Scratch option, FX Toggle Buttons, etc... 

**Code optimization:** Code reviewed for un-used functions and variable scoping

**Mapping upgrades:** Lots of changes versus last published **version v12**

Here : https://mixxx.discourse.group/t/numark-mixstream-pro-mapping/24858/33?u=ptrex

Changes : 
* Added MoveFocusForward and show_microphone binding
* Many variables are now declared with let instead of var
* pregain value now set during play_aux_1
* Play button is now a script with shift support
* Track_loaded now removes loops and only sets LEDs on hotcue buttons that are loaded
* Hotcue toggle now works when the song is playing
* Saved loops can now be triggered from a hotcue
* Default autoloop is doubled

This version has been tested on **MIXXX 2.5.0**
