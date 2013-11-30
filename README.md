# Sublime Text 2 Theme: Vim Blackboard

<a href="https://raw.github.com/wiki/oubiwann/vim-blackboard-sublime-theme/images/Sublime-VimBlackboard.png">
  <img style="float:right" src="https://raw.github.com/wiki/oubiwann/vim-blackboard-sublime-theme/images/Sublime-VimBlackboard-small.png" />
</a>

This repo is for the Sublime Text 2 theme that is meant to be installed with
Package Control. If you are looking for the version of the theme that is
manually installed, the code and instructions for that are
<a href="https://github.com/oubiwann/Theme-VimBlackboard">here</a>.


## About

The syntax highlighting in VimBlackboard is based on Blackboard (as one might
imagine), but with many of the colors changed to resemble the default Vim colors
used on dark terminals in various Linux distros from the late 90s and early
00s.

The widget theme is derived from [Soda Dark] (https://github.com/buymeasoda/soda-theme).


## Installation

Blackboard is a Sublime package. To install it:

1. Be sure to have Package Control installed.

1. Go to Sublime Text 2 -> Preferences -> Package Control -> install package

1. Type "Theme - Vim Blackboard"

1. Select it and restart Sublime after it has installed

1. Activate the theme by modifying your User Preferences to include the
   following:

    ```javascript
    {
      "theme": "VimBlackboard.sublime-theme",
      "color_scheme": "Packages/Theme - VimBlackboard/VimBlackboard.tmTheme"
    }
    ```
    If you need help locating your user preferences file, you can find it
    selecting "Preferences > Settings - User".

1. Tweak futher by adding folder icons and classic tabs:

    ```javascript
    {
      "vimbb_folder_icons": true,
      "vimbb_classic_tabs": true
    }
    ```
1.  In order to see the UI changes you will need to restart Sublime Text.
