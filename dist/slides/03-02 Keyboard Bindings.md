<!-- .slide: data-state="title" -->
# Learning Atom
Keyboard Bindings

> > Author Notes:


# Introduction
If the only thing you want to do



When you go to the preferences panel and you hit keybindings, you can take a look at what all of the keyboard combinations are for your platform. So, this is actually a great way to look for a combination...it's sort of the ultimate cheat sheet.

This table is divided into four parts. First is the keystroke combination, next is the command...or what it's actually doing. The next column shows you where that command key is coming from.

Atom is extremely modular, so a lot of the functionality comes from different packages that can be installed and uninstalled. Even the default installation has a lot of functionality added as packages and this column shows you where keybindings might be customized. Finally, you can see that there is a selector column. That is an identifier that lets you see under which conditions the keymap will become available.

In other words, not all keystrokes are available everywhere, and if this looks familiar to you web developers, that's because Atom is built on a web platform, so what you see here are the names of classes and html elements.

Keybindings work by determining first which element a keypress occurs under.

Let's say you want to edit a keybinding. The best way to do that is to add a file with your own custom key bindings that replace what Atom's defaults are.

First, go to the keybindings preferences, then find the binding you want. In the last video, I showed you a really cool binding for adding a selection above or below the current line, but I highlighted a problem because those keys are assigned to some system commands.

Search for:
add-selection

Open your keybdindings, then paste and modify what it says.

ctrl-shift-down
ctrl-shift-up

ctrl
shift
alt
cmd
up, down, right, left

This type of file is called a cson file. It's just like JSON without the punctuation, but that means that the indentation is significant.

# Keybinder resolver
If you're having trouble with some command keys, you can use a package called the keybinder resolver.
cmd-. or with “Key Binding Resolver: Show” from the Command palette. With the keybinding resolver shown, hit a keystroke:

Let's delete the other keybinding changes and say that you were trying to create a different keybinnding to toggle-line-comments.

'atom-workspace atom-text-editor:not([mini])':
  'ctrl-shift-down': 'editor:toggle-line-comments'



# Conclusion
Working with shortcuts can help you do things faster and more efficiently.
