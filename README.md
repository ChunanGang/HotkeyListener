# HotkeyListener
A tool that, after you provide a hot key combination and a program, whenever you press the hot key it will run the program. 

## Usage:
  
    HotkeyListener.exe -hotkey HOT_KEY_COMBINATION -program COMMAND_TO_RUN
 
 Example
    
    HotkeyListener.exe -hotkey SHIFT+CONTROL+T -program "C:\somePorgram.exe -mode light -autostop false"
   
After you ran this, you can switch to any other app. Whenever you press shift + control + T, C:\somePorgram.exe will be run automatically with the arguments .

Until you shun down HotkeyListener.exe with control+c.
