- You only need basic Windows usage knowledge.
- Goto   https://github.com/JohnDoe-473/Rooting-Neo-X6
- Download  'Rooting Minix Neo-X6.zip'  then unzip the file

o - - - - - o - - - - -     Step 1 (Prep Work)    - - - - - o - - - - - o
- Goto   https://github.com/JohnDoe-473/Rooting-Neo-X6
- Download  'Rooting Minix Neo-X6.zip'  then unzip it anywhere you like. You should  see 4 files inside.
- Make a directory in C Drive. Name it NEO-X6    (C:\NEO-X6\)
- Move those 4 files in here (Batch files were written to work with files in this directory)
- You'd see  'Rooting Neo-X6.txt'  with the instructions  you're reading right now.

o - - - - - o - - - - -     Step 2    - - - - - o - - - - - o - - - - - o - - - - - o
- Rooting this way will not affect  your current installed apps in anyway. Everything safe and stay the ways they are.
- Connect the male-to-male USB Cable between PC (any USB)  and X-6  (OTG only)
- Where to find the OTG port on the X-6 ? ==> When facing the side where the power button is, 
  It's the 2nd USB port  [ Power Button --- SIM --- USB1 --- USB2 <== it's this one ]
- In Settings --> Security :  Turn on Unknown sources
- In Settings: Make yourself a Developer status (click on Build number 6 times)
- In Settings --> Developer options --> Turn-on USB debugging (Important: This make windows recognize X-6)
- Double click on  '1. Install Rooted Boot image.bat' to run the batch file. Instructions will be executed, Neo-X6 will reboot automatically.

o - - - - - o - - - - -     Step 3    - - - - - o - - - - - o - - - - - o - - - - - o
- After rebooting, a new app Magisk 'module'  will be added to the App list
- Connect to the internet
- Click on  Magisk module, hit 'OK' to upgrade to full Magisk. Install the full App.
- If  you open Magisk now, you see  'Abnormal State ... bah..bah..bah'  complaint
 Short answer : Magisk is Newer. But  Titanium and the Neo-X6 are ancient. Conflict is bound to happen. 
 Old legacy apps such as Titanium Backup's 1st pick will choose SuperSU but newer ones will go for  Magisk to grant root access.
 SuperSU and Magisk are trying to fight for control (We need to delete SuperSU)
- Turn off then back on 'USB debugging' option, This will connect the PC to X-6 again (You should heard a beep)
- Double click on   '2. Remove Conflict in Magisk.bat'  to run the batch file. 
- Important : A box will show up on the screen, Click okay to grant root permission. (Hurry, you only got 10 seconds before it goes away.)
  A lot of people missed this. If this time or the next time, some programs try to ask for Root permission and if  you missed it, 
 you won't get a second chance. Magisk took the 'missed it and forget it'  approach and won't ask again. You have to open Magisk app, 
 Find those 4 icons at the very bottom, Click on the Second shield icon that look like the police badge. 
 You can manually to enable/disable apps to have 'Root right'  from there.
- Since default time-out for Magisk is a little short, Go to Settings --> Request Timeout --> select 60 seconds
- It's probably not necessary  but I would just reboot the Neo X-6 once, just to be safe.


<p align="center">  
    <img src="https://visitor-badge.laobi.icu/badge?page_id=JohnDoe-473.Rooting-Neo-X6" />  
</p>  
