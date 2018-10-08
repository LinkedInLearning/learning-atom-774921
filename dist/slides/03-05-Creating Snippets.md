<!-- .slide: data-state="title" -->
# Learning Atom
Creating Snippets

> > Author Notes:

# Introduction
Atom comes with a number of excellent snippets that you can use. As I mentioned before, snippets are context sensitive, so they become available depending on where you are on the document and the type of document you're using.

This functionality is available through the syntax package. You can see what snippets available to you.

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
