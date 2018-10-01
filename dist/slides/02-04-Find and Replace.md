<!-- .slide: data-state="title" -->
# Learning Atom
Find and Replace

> > Author Notes:

# Introduction
Every editor has a find and replace panel that lets you look through one or more documents and find or replace content. Let's take a look at the options available through Atom.

I'm going to open up a much larger project I have here in a folder called atom.

##Find
Of course, another way to navigate a document is to use the find command, which is command-f (control-f on PCs). That will allow you to search through the current document, which Atom calls the buffer.
T
Let's look for a section tag:
section

Notice that Atom highlights all of the elements that match the search criteria in the current document.

Once you find an item, you can navigate through the items that matches the search by using Command-G (That's F3 on a PC) or hit the find next button.

To find the previous element, you can use Command-shift-G or Shift F3 on a mac.

To hide the find window, you can hit the escape key.

Let's bring that back up and see some of the other options.

There are four option buttons to the right of the pane. The first is to allow you to use regular expressions to do a search. That can be a really powerful tool to let you find content.

If you turn that on you can use special characters in the search. <a href=".*">.*</a>

. Any character
* 0 or more
\d digit
\w

[Using Regular Expressions](http://www.lynda.com/Regular-Expressions-tutorials/Using-Regular-Expressions/85870-2.html)

Let's talk about the other three options. First is a toggle for case sensitivity. That means that it will only match if the word matches the capitalization. (search for his)

The second option lets you find or replace a word only if it's within the current selection. Let's see how that works.

The last option is to do a search only if the entire word matches. (search for us)

You can also search through all of the documents in the current page, by using command-shift-f (control-shift-f on PCs).The

Another good tip is that you can use the up and down arrows to go through your previous searches.

# Conclusion
Mastering the find and replace panel is a great way to find items in Atom, especially when looking for content that's in multiple files.
