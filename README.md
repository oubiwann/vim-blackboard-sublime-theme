# VimBlackboard

<a href="https://raw.github.com/oubiwann/Theme-VimBlackboard/master/Sublime-VimBlackboard.png">
  <img style="float:right" src="Sublime-VimBlackboard-small.png" />
</a>

## About

VimBlackboard is a simple theme based on Blackboard (as one might imagine).
Blackboard, in turn, is mostly derived from
[Flatland](https://github.com/thinkpixellab/flatland), the right place to start
for any custom theme development for Sublime. Thanks Flatland!


## Installation
Blackboard is a Sublime package. To install it:

1. Make a home for your code and then go there, e.g.
```
mkdir ~/lab/SublimeText
cd ~/lab/SublimeText
```
2. Clone the repo:
```
git clone https://github.com/oubiwann/Theme-VimBlackboard.git
```
3. Change dir to your
   Sublime Text 2 Packages directory. You can find that directory by selecting
   "Preferences > Browse Packages ...".
4. From the package directory, link to your checkout:
```
ln -s ~/lab/SublimeText/Theme-VimBlackboard/Theme\ -\ VimBlackboard .
```
5. Activate the theme by modifying your user preferences to include the
   following:

```javascript
{
  "theme": "VimBlackboard.sublime-theme",
  "color_scheme": "Packages/Theme-VimBlackboard/Theme - VimBlackboard/VimBlackboard.tmtheme"
}
```

If you need help locating your user preferences file, you can find it selecting
"Preferences > Settings - User".
