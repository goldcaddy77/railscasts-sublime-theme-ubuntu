# Sublime Text 2 - RailsCasts Theme Installer

SublimeText port of [Ryan Bates](http://railscasts.com/about)' [TextMate theme](http://media.railscasts.com/resources/textmate_theme.zip) and a bash script to install the theme.

## Installation

### Using Included Script
Note: the paths in the included script assume you've installed Sublime Text via the [Sublime Text 2 Ubuntu PPA](http://www.webupd8.org/2011/03/sublime-text-2-ubuntu-ppa.html).  If you have installed Sublime Text manually, you'll likely need to modify the paths in the script.

```sh
cd ~/.config/sublime-text-2/Packages/
git clone git://github.com/goldcaddy77/railscasts-sublime-theme-ubuntu.git "Theme - RailsCasts"
cd "Theme - RailsCasts" && ./install
```

After the script completes, it should have added 2 lines to the bottom of your /Packages/User/Preferences.sublime-settings file and opened this in Sublime Text.  Merge these configuration settings into the settings hash:

#### Before
![Before](http://i.imgur.com/ujurS10.jpg "Before")

Just grab the 2 lines circled above and merge them into the hash so it looks like this:

#### After
![After](http://i.imgur.com/TajUHbs.jpg "After")

The theme should pick up when you save the settings file.

### Font

The code font shown in the RailsCasts is [Bitstream Vera Sans Mono](http://www-old.gnome.org/fonts/).  It is automatically downloaded and installed from [here](http://ftp.gnome.org/pub/GNOME/sources/ttf-bitstream-vera/1.10/ttf-bitstream-vera-1.10.tar.gz)

## License

RailsCasts Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share the theme.

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on RailsCasts Theme by Ryan Bates ([http://railscasts.com/](http://railscasts.com/))

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "RailsCasts Theme" (or a close variant) in the main project title, repo name or Package Control name.