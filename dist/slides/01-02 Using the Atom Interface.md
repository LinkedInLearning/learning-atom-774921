<!-- .slide: data-state="title" -->

# Learning Atom

Using the Atom Interface

> > Author Notes:

# Introduction

Let's take a look at an overview of the main components of the Atom interface.

Let's go ahead and launch atom. When you launch atom for the first time, it should open an empty document by itself. This shows you the basic parts of the interface.

## Panes

Atom is divided into visual sections called Panes. There are four basic panes in the window we just launched.

First, is the tab bar...every document gets placed in a tab at the top of the screen and if we had more than one document we'd see more.

Second is the gutter (which has line numbers in it. Right now we don't have any text so there's just a number one there.)

Third is the status bar at the bottom of the screen where you can see some information about the document.

Finally, the text editor where you do most of your work. There's a thin line at about 80 characters from the left. That is the wrap guide, letting you know that if you're writing code wider than this, then it's probably getting too long.

## Macros

Atom comes with some built in macros, but they're context sensitive. Since we're got an unidentified document, there are very few of them.

Let's go ahead and type `Lorem` and then tab. You can see some basic Lorem Ipsum text, which is often used by designers and developers to mock up interfaces. It's fake greek.

Another available Macro is some default copyright text. Let's go ahead and type an `L` and use the copyright.

## Status Bar

Take a look at the status bar. It shows the name of the file. If you've made changes to the file, but haven't saved them, it will also show an asterisk next to the name.

You can click on the name of the file and Atom will copy the path to that file to the clipboard. Right now, it just says untitled because that document is not saved.

Next to the filename, you'll notice a line number indicator. The number before the colon shows you the line number, the one on the right shows the column number, which is the number of character from the beginning of the line. You can click on that to go to another location in the document.

On the right of the status bar there is some information about the document, including a line ending format. In some machines, you have to specify wether the line endings are saved in a windows format (CRLF) or a Unix format (LF) or mixed. You can click on that to change it as well.

To the right of that, you'll notice the format of the current document. Atom will do it's best to try to autodetect the format of the document based on it's contents or by the extension. You can click on this to force it to think of the document as having a different format, but most of the time, it's best to leave the default, which is autodetect.

## Tree View Pane

We haven't saved this file, so let's go ahead and do that.

I'm going to create a new folder called temp and then save this file as an html document called index.html

When you do that, the tree view will appear with the structure of the folder and the file. Notice that since we saved a file, we can now click on the index.html in the status bar to copy the path and now there's a new option to copy a relative or an absolute path.

You can show or hide the tree view by hitting `cmd \`--mac `ctrl-\`--pc

You can also show and hide the tree view by using Atom's

You can also give the tree view focus while on any other view to the tree view by hitting `control-0`.

## Tree View

You can perform any number of operations in this tree view, so you can create new files, new folders, rename files, etc. The easiest way to do that is to `right click` somewhere in the tree view and choose what you want to do from the popup menu.

You can also click and drag the dividing line between the editor and the tree view to resize of the tree view. If you double click on this line, it will resize automatically to fit the longest file name in the tree view, which is quite handy when you want to minimize things.

Also, because we saved the file with an extension, Atom switched the type of the document to HTML. That exposes some new snippets that we can use to work with our document.

## Create an HTML document.

Now, for example, we have a macro to create HTML documents. just type in `html` and hit tab.

## Tabs

When you click on a document, it will open in a new tab. You can switch between tabs by hitting `alt-cmd` and the left and right arrow on a Mac. On a PC, it's `control-pageup` and `control-pagedown`. You can also move tabs around by clicking and dragging them.

##Increasing the font size
There's something else I want to do before I go further, The font on the document is a bit small and for this course, so we can change that by going to the view menu and choosing increase font size a few times. Note the keyboard shortcuts.

# Conclusion

There's quite a lot of power in the default Atom Interface. Atom is probably the most customizable editor, so you can also reconfigure how any of these elements look and work.
