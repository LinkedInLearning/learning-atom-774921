<!-- .slide: data-state="title" -->
# Learning Atom
Working with Git

> > Author Notes:

# Introduction
Atom was created by Github and was originally an internal project...and if I was creating a custom editor for myself, I would throw in some extra features in there that would work well for my company. Sure enough Atom has some great built in features that integrate with Git/Github projects.

Now before I go any further, let me just say that these next few videos are a bit advanced and meant only for folks who want to know how to use Atom with Git and Github, but it's not a Git course, so I'm not going to talk about how to create repos or manage them. I'm going to assume you already know how to do that.

So, if you haven't used Git or Github before, you can skip these next few videos, I would suggest that you watch [Up and Running with Git and Github](http://www.lynda.com/Git-tutorials/Up-Running-Git-GitHub/409275-2.html)

Because the project that I've been working on is a git project. You the interface in Atom is a bit different. For example, if you look down at the status bar, you can see that we have some additional informatino. For example, the name of the current branch.

To the right of that. If you've made any changes to the current branch. Atom will tell you how far away from that branch you are. Let's delete the history section from our document.

Now if you see the status bar, you can see that there are -11 lines of difference between our version and the last commit.

Also, notice that we get a subtle visual cue in the gutter. There is a highlight that shows us where we made the deletion.

If you add some changes, you can also see that the indicator shows you a different color when changes have been made.

Let's make some changes to the document and see what happens. The status bar shows how many additions we've made and how many deletions.

Now, of course, we could just do an undo command to go back to the point of our commit, but what if we close the document or if we made changes to multiple documents. Our ability to undo would be gone.

Let's click on another file. Notice that the tree view also has color coding that shows us that some of these files are different than what's in the last commit.

## Review Documents


Now, as you might now, there's a way to take a look at the documents that are currently open in your project. It's command-b on the mac. Control-b on a PC. If you're working with a git project and you've made some modifications, you'll see that an icon appears next to the filename.

If you hit command-shift-b or control-shift-b on the PC, you'll be able to see only the files that have been untracked or modified. This is the same list you'd see if you ran a git status command. It doesn't matter how many other tabs you have open, or if you even have any tabs open at all.

## Reset HEAD

Let's say that you've tried some things in your project and now you want to take things back to the way they used to be in the last commit. I could do that via the terminal, but you can do that with a simple command key.

command-option-z or control-alt-z on a PC will let you check out the HEAD revision of the current file in the editor. This is the same as running a git checkout head and git reset head command in the terminal.

If you didn't mean to do that, not to worry, it goes onto the undo stack so you can easily use command-z afterwards to reset.

# Conclusion
If you're already using Git to manage your projects, these very subtle visual cues are going to help you take less trips to the terminal...and that's always good.
