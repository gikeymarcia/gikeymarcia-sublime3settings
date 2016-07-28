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

5. Install Monaco font 'monaca.ttf-master/monaco.ttf'

6. Turn on Sublime Text 3 and it should all spin up and go after a few restarts
