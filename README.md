
 = = = =  With ADB method   = = = = = = = = = = = = = 
o - - - - - o - - - - -     Step 1    - - - - - o - - - - - o - - - - - o - - - - - o
- Rooting this way will not affect  your current installed apps in anyway. Everything safe and stay the ways they are.
- Connect the male-to-male USB Cable between PC (any USB)  and X-6  (OTG only)
- Where to find the OTG port on the X-6 ? ==> When facing the side where the power button is, 
  It's the 2nd USB port  [ Power button --- SIM --- USB1 --- USB2 <== it's this one ]
- In Settings --> Security :  Turn on Unknown sources
- In Settings: Make yourself a Developer status (click on Build number 6 times)
- In Settings --> Developer options --> Turn-on USB debugging (Important: This make windows recognize X-6)
- Go inside C:\NEO-X6 folder and double click on  '1. Install Rooted Boot image.bat'
o - - - - - o - - - - -     Step 2    - - - - - o - - - - - o - - - - - o - - - - - o
- After rebooting, a new app Magisk 'module'  will be added
- Connect to the internet
- Click on  Magisk module, hit 'OK' to upgrade to full Magisk. Install the full App.
- If  you open Magisk now, you see  "Abnormal State ... bah..bah..bah" complaint
Short answer : Magisk is Newer. But  Titanium and the Neo-X6 are ancient. Conflict is bound to happen. Old legacy apps like Titanium Backup's 1st pick will choose SuperSU but newer ones will go for  Magisk.
SuperSU and Magisk are trying to fight for control (We need to delete SuperSU)
- Turn off then back on "USB debugging" option, This will connect to X-6 again (Should heard a beep)
- Go inside C:\NEO-X6 folder and double click on   '2. Remove Conflict in Magisk.bat'
- Important : A box will show up on the screen, Click okay to grant root permission.
A lot of people missed this. If this time or the next time, some programs try to ask for Root permission and you missed it, you won't get a second chance. Magisk took the "missed it and forget it" approach. You have to open Magisk app, go for the 4 icons at the very bottom, Click on the Second shield icon that look like the police badge. You can enable/disable it from there.
- Since default time out is a little short, Go to Settings --> Request Timeout --> 60 seconds
- It's probably not necessary  but I would just reboot the device once just to be safe.
