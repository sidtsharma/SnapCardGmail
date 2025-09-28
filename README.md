-------Snap Card Game ------------

Zip file contains three folder 
  
  1. Code
  2. Setup
  3. Exe

You can run the code through exe or run a setup file.

It's a console program It will take few inputs like 

  1. Number of Packs - It must take an input as a non negative absolute number as an integer.
  2. Select Matching conditions - Here you have three option to play 
        1. Play with face value only
        2. Play with suit Only
        3. Both.
  3. It will ask you to enter the players name.
  
After all these correct input it will run till any one of them is not win.

Add few configuration for log file and add delay in console.
----------------GOS.exe.config ---------------
 <appSettings>
    <add key="EnableLogging" value="true" />
    <add key="PlayDelayMilliseconds" value="1" />
  </appSettings>


----------Improvements -----------------------
App is slow down if integer number for pack is big.  
 
