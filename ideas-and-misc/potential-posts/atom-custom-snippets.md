## Making Custom Snippets in Atom

I have been using atom for about a month now. It has quickly become my editor of choice after using Emacs for most of my coding career. Coming from an editor like Emacs, I am used to having the option to customize almost anything I would like to and as I have used Atom, I have looked to make some of the customizations that I like to use.

## Snippets

One of these customizations are 'Snippets'. They are basically autocomplete for code, similar to how [TextExpander](http://textexpander.com) works. Not only were there a couple custom snippets I wanted to add, but I also wanted to change some of the default options since I used [Standard]() for formatting my Javascript and end up having to remove a lot of semi-colons from the default Javascript snippets to stay within the style.

## Using Snippets

### By Searching All Available

To use snippets, you simply can hit `⌥ + ⇧ + s` and a list of all available snippets for that file type (javascript, html, ruby, ect) will appear. You can scroll through the list or you can search for something specifically.

### By Shortcut

Most snippets have a shortcut associated with them. You can see this next to the name of the snippet when you search for it or you may see it as an autocomplete option as you are typing some code. This is my preferred usage of snippets. Let's see one of these in action:
1) Open up a javascript (.js) file.
2) Type `expmod` in the file. When you see the autocomplete show, hit enter on that shortcut.
3) You should see it auto fill with:
  ```
    module.exports = name;
  ```

Pretty cool right? Lets try one more:

1) In the same file
2) Type `req` at the top. When you see the autocomplete show, hit enter.
3) You should see it auto fill with:
  ```
    require('module');
  ```

Again, really cool. It even places our cursor in the proper place to begin editing the code and adding the name we need. 

## Making Snippets

Custom snippets are easy enough to make, however the documentation on doing so is missing a couple steps, so I figured writing down the current way to do it would be beneficial.
