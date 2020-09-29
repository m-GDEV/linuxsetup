# How to make a desktop shortcut for a python script.


## STEP 1:

Copy file from actual location and put it into CD folder

## STEP 2:

Add: ```#!/usr/bin/env python3``` to the top of file

## STEP 3:

make file executable by navigating to dir in terminal and then run:

```chmod +x examplefile.py```

After that, verify that it is indeed executable by running ```./examplefile.py``` in the CD dir

## STEP 3:

find suitable icon for shortcut

## STEP 4:

Create a new file on the desktop and name it whatever you desire, make sure the extension is:
``` .desktop ```
### Example: 
```
[Desktop Entry]
Version=1.0
Name = ENTER NAME OF SHORTCUT
Exec = PUT PATH OF YOUR FILE (USE 'sakura -e' IF SCRIPT RUNS IN TERMINAL)
Icon = PUT PATH FOR ICON OF SHORTCUT
Type = Application
Terminal = TRUE/FALSE
```


## STEP 5:

DONE!
