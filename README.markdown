What this script does
---------------------
Downloads a random xkcd comic from xkcd.com and sets it as your desktop background. Only works with GNOME for the moment. You can also run the script from cron in a minute interval 

How to use it
-------------
Get `xkcd_wallpaper.sh` either by cloning the github project or downloading the file. Run it from the terminal, with a keyboard shortcut or with a custom application launcher. You can run the script with `sh xkcd_wallpaper.sh` or `./xkcd_wallpaper.sh`. The file `current_xkcd_wallpaper.(png | jpg)` gets saved in your home directory `xkcd_wallpaper`. 

For cron to run use the following command
*/1 * * * * <present_working_directory_where_your_script_resides>/wallpaper.sh

Additional remarks
-----------------

* Running the script with a keyboard shortcut set in the ubuntu Keyboard Shortcuts menu does not work for the moment. It does work with compiz keyboard shortcuts though. 
* If you have any feedback (negative or positive) drop me an e-mail at basil.philipp@gmail.com

Future features
---------------
* Display titles.
* Make it possible to choose the location where the picture file gets saved.
* Update background when new comic is published.
