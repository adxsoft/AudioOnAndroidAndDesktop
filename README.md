# AudioOnAndroidAndDesktop

A Livecode stack to test various audio formats on multiple platforms
Currently has only been tested on Mac OSX 11.5 and Android Jelly Bean

This repository contains the livecode source and the sound files.

Instructions
1. Download this repository as a zip file
2. Unzip into a folder eg myAudioTest
3. Load AudioOnAndroidAndDesktop.livecode into Livecode (I used Livecode 9.0, app may work with older versions - no guarantees)
4. Create a standalone app for your target platform
5. put the app into the folder (myAudioTest)
6. Run the App

If you just want to run app from within Livecode then the sound files will need to be in the same location as the AudioOnAndroidAndDesktop.livecode file.

If you are testing on Windows or Linux then please comment on the forum post https://forums.livecode.com/viewtopic.php?f=8&t=32213&p=176880#p176880

My testing so far shows WAV files to be the most portable for both the Player control and the play audioclip command.
