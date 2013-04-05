CoverflowAltTab
================

CoverflowAltTab is an Alt-Tab replacement available as an extension for [Gnome-Shell](http://www.gnome.org/gnome-3/) and [Cinnamon](http://cinnamon.linuxmint.com/).

It let's you Alt-Tab through your windows in a cover-flow manner.

Originally this was a port of the CoverflowAltTab extension for Gnome-Shell by [palatis](http://code.google.com/p/gnome-shell-extensions-coverflowalttab/) and the recent rewrite with lots of improvements was done by [Lusito](https://github.com/Lusito), so a big thanks and all the glory to them!



![Screenshot](http://www.dmo60.de/CoverflowAltTabScreenshotkleinneu.jpg)




Installation
-------------

Thanks to Lusito, the master branch now supports both Gnome-Shell(>3.2) and Cinnamon. For Gnome-Shell version 3.2 there is a separate branch, but it is not further maintained.

#### Gnome-Shell ####

Easiest way to install the extension is via [extensions.gnome.org](https://extensions.gnome.org/extension/97/coverflow-alt-tab/), the official Gnome3 extension platform. Head over there and istall CoverflowAltTab with one click by toggling the switch on the site.

If you want to install it manually (e.g. to test the latest, probably unstable code), download the zip file by clicking the zip button on the upper part of this page and extract it.

  1. Copy the folder "CoverflowAltTab@dmo60.de" to `~/.local/share/gnome-shell/extensions/`.
		
  2. Use Gnome-Tweak-Tool or [extensions.gnome.org](https://extensions.gnome.org/local/) to enable the extension. (Eventually you have to restart Gnome-Shell: Press Alt+F2, type 'r' and enter)
	

#### Cinnamon ####

Grab the zip file from [Cinnamon-Spices](http://cinnamon-spices.linuxmint.com/extensions/view/3) (recommended) or by clicking the zip button on the upper part of this page (this way, you will get the latest, maybe unstable code) and extract it.

  1. Copy the folder "CoverflowAltTab@dmo60.de" to `~/.local/share/cinnamon/extensions/`.
	
  2. Enable the extension in Cinnamon Settings. (Eventually you have to restart Cinnamon: Press Alt+F2, type 'r' and enter)
	 



Usage
------

This extension uses the following key bindings (you can change or disable them in your system settings):

  - "Switch applications" (usually **Alt+Tab**): Cycle through all windows from the current workspace
  - "Switch windows of an application" (usually **Ctrl+Tab**): Cycle through all windows from the current application from all workspaces
  - "Switch system controls" (usually **Ctrl+Alt+Tab**): Cycle through all windows from all workspaces (who wants to cycle through system controls anyway?)
    
All of the shortcuts with **Shift** key pressed cycles backward.

  - Hit **Esc** to cancel.
  - Hit **q** to close highlighted window.
  - Hit **d** to hide all windows and show the desktop.

You can also use the **arrow keys** or your **mouse wheel** to cycle through the windows. 




Customization
--------------

To change the keybindings, use your system keyboard settings! See above for the used keybindings and change them to your desire.

Recently we have added a second Animation style you can use instead of the Coverflow one. It is called 'Timeline' and was inspired by the Windows 7 Super-Tab switcher. You can activate it in the extension preferences. Check it out!

#### Gnome-Shell ####

Click the preferences button on [extensions.gnome.org](https://extensions.gnome.org/local/) or launch `gnome-shell-extension-prefs` from a terminal and select 'Coverflow Alt-Tab'. This will show you a preference dialog where you can change the settings to your needs.

#### Cinnamon ####

Since Cinnamon 1.8, you can use 'Cinnamon-Settings'/'System-Settings' to change the extension preferences. Go to section 'Extensions', select Coverflow Alt-Tab and click the configure button.

For older Cinnamon versions, you have to go the extension's installation directory and open the file `config.js`. There you can change all the preference values, just not as pretty as with a configuration dialog.
