# SetAllFakeUsers2.8
Blender addon for setting all fake users in datablocks.

## Why
Makes it easy to:  
* Add fake users to everything if you want to keep everything in the blend file.  
* Remove fake users from unused content to decrease the blend file's size.  

## Installation  
### Requirements  
Works on Windows, Mac, and Linux.  
Meant for Blender 2.8 Beta
### How to Install  
Download the python file (put it in a place where you can easily find it, like your desktop)  
In Blender's settings, go to the addons tab  
At the bottom, click "Install from File"  
Find where you put the python file, select it, and click "Install from File" 

## Using
1. Run the operator from...
* File menu > External Data > Set All Fake Users
* Operator Search > Set All Fake Users  
2. A dialog will appear. Set the action to add or remove, and check the datablocks you want to change.
3. Click "Done" at the bottom of the dialog.  

## Notes
The UI may not update automatically to show the change to fake users.  
To fix this, move your mouse cursor over the fake user icon, and it should update.
