<!-- .slide: data-state="title" -->
# Learning Atom
Creating Snippets

> > Author Notes:

# Introduction
Atom comes with a number of excellent snippets that you can use. As I mentioned before, snippets are context sensitive, so they become available depending on where you are on the document and the type of document you're using.

This functionality is available through the snippets package. You can see what snippets available to you by going to this snippet. This will show you any custom snippet that is available for the current language.

You can also create your own snippets using the snippets menu item. Let's use the command palette (command-shift-p/control-shift-p) and look for snippets. You can also find them in your menus. Open your snippets.

You can create your own snippets.

snip

The first thing type is the scope, which is where this snippet will apply. Look for the individual language package and then the scope text.

Let's create a snippet that works in HTML.

Snippets use a format called cson, which is like the json format without the curly braces and where indentation is meaninful.

```
'.text.html':
  'viewport':
    'prefix': 'viewp'
    'body': '<meta name="viewport" content="width=device-width">'

  'li anchor':
    'prefix': 'lia'
    'body': '<li><a href="${1:http://}">$2</a></li>'
  'classed list':
    'prefix': 'ulit'
    'body': '''<ul>
      <li class="${1:item}">$2</li>
      <li class="${1:item}">$3</li>
      <li class="${1:item}">$4</li>
    </ul>
    '''
```

# Conclusion
Snippets are one of the ultimate customizations in Atom, you can really.
