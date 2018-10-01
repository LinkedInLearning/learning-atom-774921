<!-- .slide: data-state="title" -->
# Learning Atom
Selections &amp; Multiple Cursors

> > Author Notes:

# Introduction
Atom has all of the traditional ways of selecting elements that are common on other applications as well as some really interesting ways of selecting things.


## Traditional
You can of course make a selection by performing different mouse actions like clicking and dragging. Double clicking on a word selects the word, triple clicking selects the whole line.

You can also choose an entire line by clicking on the line numbers.

If you have an active selection, you can expand it by holding down the shift key. For example, I can add to a selection by holding down the shift and pressing up.

Holding the option (that's alt on a PC) while holding the shift key with the left and right arrow keys adds a word to the selection as well.

To select to the beginning of the document, you can use command-shift-up. This is control-home on the PC. Command-shift-down lets you select to the end of the document (that's control-shift and the end key on a PC)

Command-A (control-a on a PC) lets you choose the entire document.

If you press command-l (control-l on a PC) it will select the whole line.


## Multiple Cursors

If I had to name the one feature I used the most in Atom is the ability to work with multiple cursors. It's a feature that I originally fell in love with in Sublime Text...another great editor. Atom's implementation is a bit different, but just as awesome.

The easiest way to see this at work is by selecting something on your document. Let's select the text class="container" and then press command-D, that's control-D on a PC. That will select the next word that matches what you have selected.

After you do that, you can simply type in a replacement word. With these multiple cursors, you can continue to perform other selections.

If you don't want to have to hit the keyboard sequence a bunch of times, you can simply make the selection, then hit control-command-G (Atl-F3 on a PC) and that will activate all of the similar selections at once.

You can create another cursor anywhere in your document, by command clicking (control-clicking on a PC). Then, you can use any normal editing commands that expand or modify the selection. So for example, I can use option-shift and the arrow keys to expand the selection at each cursor.

You can modify a selection so that a cursor is placed on every line by making a selection, and then choosing command-shift-L. Now PCs or Linux users don't have this key binding, but you can still select it from the menu. It's called split into lines. There are some other interesting options in the select menu that you can check out, but I think they're not as useful as the ones we've talked about.

This next one is sort of tricky, but really useful. You can add a cursor at the same position directly beneath the current line by using control-shift-up or control-shift-down on a mac (Alt-Control-Up or Alt-Control-Down). Now, before, you do that, On my machine, those keys are mapped to some Mission Control actions. You can change that by going to the keyboard system preference, then clicking on mission control and turning those off.


# Conclusion
Working with multiple cursors is one of the most useful techniques you'll learn when using Atom, so make sure you take some time to practice some of these shortcuts. In order to learn these and have them become truly useful, you'll need to do them several times.
