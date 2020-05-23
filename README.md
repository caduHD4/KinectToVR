# KinectToVR
KinectToVR is a synregic combination of head tracking (yes, it's free),    
full body trackers and controllers support, that finally gives you software    
to track your body that is free, won't crash and doesn't need some weird inputemulator to basic work.    
(It still needs it, modified, for head tracking, if you like to do so)    

## Getting Started - Users
Download release, unpack somewhere on dektop and run \[register_driver.bat]    
You can run kinecttovr or steamvr - from time to time it will work by launching only k2, then vr will start sutomatically.     
If you are using head tracking, please backup your inputemulator dll and replace it with one provided in release.    
In any other ways, don't do it. You just don't need to change, etc.    
(OVRIE dll is located at SteamVR/drivers/00vrinputemulator/bin/win64/)    
    
Full body calibration:    
- Step 1: stand somewhere - upright or something like that    
- Step 2: stand somewhere else - maybe on left    
- Step 3: stand somewhere else - go back and crouch or fly    
- Step 4: stand at your playspace origin and look at kinect - this will orientate trackers    
     
Controllers calibration:    
- Controllers use full body calibration variables    
    
Head tracking calibration:    
- Just look at kinect    

## *The Official Discord is [here](https://discord.gg/Mu28W4N)
## *The Unofficial Discord is [here](https://discord.gg/9kJgxeH)

## Contributors of past versions
* **sharkyh20** - *Initial work* - [sharkyh20](https://github.com/sharkyh20/)
* **naelstrof** - *Playspace Movement, General Improvements* - [naelstrof](https://github.com/naelstrof/)
* **DJ Lukis.LT** - *Color Tracking Help, Project Management* - [lukis101](https://github.com/lukis101)
* **コレヂャン** - *Calibration scripts, general help (korcan)*

## License
KinectToVR is based on GPL v3, so you need to follow it.     
AND
When you use this code you __must__ describe that it's sharky's base and my addons (you see everything that i commited anyway). You cannot use this in any paid program. Copy-pasting without describing source is also prohibited. You must not change any of files and redistribute it at your own. Also, you have to tell what you exactly changed and used, when redistributing parts of code. Furthermore, when you want to redistribute software / embed it in your own application, you are supposed to tell me this directly (akayakimi@gmail.com) or via k2vr's or arduvr's discord server, mentioning me (アカヤベキミツ). Only way above restrictions don't apply is when you fork repo and clearly tell it's forked, describe which parts you have changed. Hope you'll have fun! 

## Changed so far:
* Calibration method - now it's even shorter than d4vr's one!
* Trackers implementation - K2 is now static openvr driver
* Head Tracking - yes, you can use this for tracking your head (AND NOT GET 'DIZZY')
* Controllers - ArduVR emulates index controllers with your arduino (more info at https://ovr.ayakimi.rf.gd)
* Icons of trackers - they're pucks, aren't they?
* Flip - kinect now works even if you are back to it
* Automatical spawn of trackers
* Automatical start of head tracking
* Auto start of controllers handle
* There is not need to have any controllers to calibration (you have, but it's only information)
* Synergic calibration - all at once (except when you're using head tracking)
* Deleted unused parts of program - psmoves and some weirdo stuff
* Added app icon - you want to have it!
* more and more..
