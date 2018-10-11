<!-- .slide: data-state="title" -->
# Learning Atom
Customizing Themes

> > Author Notes:



# Introduction
- [ ] Besides settings, you can customize the way themes work in a few different ways. For example, you can change an existing theme. Go to the themes list in settings, then click on the settings icon (NOT THE NAME) of the theme. From there, you should see a `view code` button.

- [ ] Once you hit the view code button, you should see a new window appear with your theme.

- [ ] If you look at the title bar, you'll see that the themes are stored inside the users folder in the invisible .atom folder inside packages. All packages and themes you've downloaded are stored here.

- [ ] The theme is composed of several folders, the lib folder has configuration files, the resources folder which you may or may not have has additional files like fonts or other things the theme requires.

- [ ] There are a bunch of other files including the ReadMe file, which is what you're looking at when you see the them information in Atom or the website.

- [ ] To customize a theme, what you're interested in is the styles folder. This has a list of all of the stylsheets for the current theme. As I mentioned it's written in a language called Less, which is related to CSS, but allows you to use variables. You can still use CSS and if you need to learn more about less, we have some great courses in the library.

- [ ] There is one file outside this folder that's really important and it's the index.less file. It shows you the list of styles and the order that they're being imported in.

- [ ] There is usually a set of variable styles that are loaded before other things, so this is a great place to play with styles.

- [ ] Change the font size. You may have to reload the window.

- [ ] Feel free to play around with the theme and remember that if you mess something up, you can just uninstall and reinstall the theme. As a measure of last resort, you can delete the .atom folder inside your users folder using a terminal to reset Atom to factory settings. 

- [ ] You can also use a package to create your own Syntax theme. These are the theme atom uses to display your code. Go to `packages: Package Generator: Create Syntax Theme`