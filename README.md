Sublime-text-configuration
==========================
This repository contains all my prefered Sublime Text 2 Configuration for itself and for my prefered packages.

In this document, each time it is written : _Open Command Palette_, you can open it in menu _Tool/Command Palette_ or with the shortcut _Shift+Ctrl+P_ on Linux.

###Sublime Text Preference Settings###

Copy the content of the file _Preferences.sublime-settings_ in your user settings. You can find it in the menu _Preference/Settings - user_.

###Install Package Control###
This package will let you to easily install others usefull packages directly in Sublime Text.
You can find it [here](https://sublime.wbond.net/installation#st2).

In the end of this document, when you modify a package setting or key binding, never modify the _Default_ file but always the _User_ file. (But read the _Default_ file to find the inspiration !)

###Package _Alignment_###
This package is usefull to align in one shortcut differents lines on the same character (by default : "_=_").
* *How to install it* : Open Command Palette, then select _Package Control: Install Package_, then select _Alignment_.
* *How to use it* : Select the text you want to align, then press the default shortcup _ctrl+alt+a_ on Linux.
You can modify the shortcut in _Preferences/Package Settings/Alignment/Key Bindings_.
You can modify the aligning character (for example to add the charachter "_=_") in  _Preferences/Package Settings/Alignment/Settings_.

My personal preference file for this package is the file _Alignment.sublime-settings_.

###Package _Bracket Highlighter_###
This package highlights brackets. It is usefull when you have several nested brackets.
* *How to install it* : Open Command Palette, then select _Package Control: Install Package_, then select _BracketHighlighter_.
* *How to use it* : There is nothing special to do, just click on a bracket and all the corresponding brackets will be highlighted.

