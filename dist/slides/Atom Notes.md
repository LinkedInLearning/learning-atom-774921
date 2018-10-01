Atom in Last Course 1.5.3

New Features to Cover

- Select to next/previous bookmark
https://github.com/atom/bookmarks/pull/91

Teletype
https://teletype.atom.io/

Atom IDE
http://blog.atom.io/2017/09/12/announcing-atom-ide.html

Github Integration
http://blog.atom.io/2017/05/16/git-and-github-integration-comes-to-atom.html

Docks
http://blog.atom.io/2017/05/23/docks-deep-dive.html

Easier to find closing brackets
https://github.com/atom/bracket-matcher/pull/290

## Move Selected Text Left and Right

This version ships with two new commands for moving text left and right by one column. By default, they are bound to cmd-ctrl-left and cmd-ctrl-right on OS X and alt-shift-left and alt-shift-right on Windows and Linux. Shoutout to @mnquintana for this new feature! :zap:



## Internals Redesign - Display Layers
We have been working on a complete restructure of the editor display layer. We plan to share all the details of this redesign in the future in a more in-depth blog post, but in the meantime here are some of the things that have been improved as part of this rewrite:

Faster editing and scrolling when soft-wrap is enabled or some text regions are folded.
Introduction of free-form folds, in addition to row-based folds, via Fold Selection (alt-cmd-ctrl-f on OS X and alt-ctrl-f on Windows and Linux).
Improved strategy when soft-wraps occur at whitespace locations.


## Drag and Drop Layout Management
Thanks to @MikeInnes, we are very proud to announce drag and drop layout management for tabs. We think this is a great feature that will make organizing your workspace even easier! :tada:

## Adding Project Folders from the Command Line
Atom now supports the --add swich (aliased to -a) which will add the passed directory as a project folder to the most recently focused Atom window instead of opening that folder in its own window.

## Keyup Keystroke Support in Keybinds
Atom’s Keymap file now supports a new syntax for dispatching events on keyup events. For example,

'atom-workspace':
  'ctrl-y ^ctrl': 'core:do-stuff'
means that the core:do-stuff command will be dispatched when the user presses ctrl-y and then releases the ctrl key. If any other binding is used instead of or after the ctrl-y, the command will not be dispatched.

You can also specify multiple events in a sequence:

'atom-workspace':
  'a b c ^c ^a ^b': 'core:secret-triple-command'
This command would be dispatched when the user presses a, b, c, then releases c, b, a; however, releasing a, b, then c would not dispatch the event.


## More Ways to Move Text
Atom 1.8-beta includes two new commands for moving text left and right by one column. They are bound to cmd-ctrl-left and cmd-ctrl-right on OS X and alt-shift-left and alt-shift-right on Windows and Linux.
