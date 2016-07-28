How to import these files. To configure your Sublime Text 3

# Windows Instructions (don't know how this works on Mac/Linux

1. Install Package Control for sublime text 3
    i. Follow instructions @ 'https://packagecontrol.io/installation'

2. Package Control will require a few restarts, do them. Once the restarts have ceased

3. Make sure you have user settings:
   Preferences > Settings - User >
   i.  If nothing exists, save an empty JSON object i.e., '{}'
   ii. Turn off Sublime Text 3

4. Delete contents of /Package/User folder
   i.  Clone git archive to this folder (don't use a sub-folder)
	C:\Users\Mikey\AppData\Roaming\Sublime Text 3\Packages\User
	It should contain a 'Preferences.sublime-settings' file (from step 3.i)

5. Make a folder for theme files in your Sublime Packages folder
   e.g., C:\Users\Mikey\AppData\Roaming\Sublime Text 3\Packages\Colorsublime - Themes\
   # you do not yet have the "Colorsublime" package but
   # it will be downloaded once we turn Sublime back on

6. Extract contents of Themes.7z to the folder from previous step

7. Install Monaco font from monaca.ttf-master/

8. Turn on Sublime Text 3 and it should all spin up and go after a few restarts 