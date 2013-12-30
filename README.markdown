# CthulhuDolorem
- thank you to billymoon for the original LoremIpsum plugin of which this is just a modification

An extension for Sublime Text 2 and 3!

_(Support for Sublime Text 3 is new, and barely tested - any feedback appreciated - see ST3 section below)_

It allow you to Insert Cthulhu Dolorem in the editor via menu items or keyboard shortcut.

Select how much text you want from the menu item in `Edit->Text->Cthulhu Dolorem` or on the right click menu in `Cthulhu Dolorem`.

Just press the shortcut key (Alt+Command+l on OSX, Control+Alt+l on Windows and Shift+Alt+l on Linux) to add Cthulhu Dolorem text. Keep pressing to add more.

Alternatively, you can also specify the number of paragraphs, by writing a number, and pressing the shortcut key. Cthulhu Dolorem will check if there is a number directly preceding the selection range, and replace it with that many paragraphs of Cthulhu Dolorem. Addind a decimal point, defines the approximate number of words per paragraph.

## Examples

Generate a dummy title for a blog, and a few paragraphs

- Press the shortcut once, to generate a single line of cthulhu dolorem, of about 10 characters
- Move down to a newline, and type `5.60` and then press the keyboard shortcut for Cthulhu Dolorem

## Features

2. Randomly generates text from selection of words
3. Always starts with `Cthulhu Dolorem` for first paragraph, and capitalizes following paragraphs
4. Leaves the inserted text un-selected, so you can insert some more straight away (rapid tapping to get as much cthulhu as you want)
5. Shortcut key, `Edit -> Text -> Cthulhu Dolorem...` sub-menu, and context menu activation
6. Variable size of text from just `a tentacle` to more than cthulhu can shake a stick at!
7. *NEW*: Specify how many paragraphs and words per paragraph you want (type a number before pressing the Cthulhu Dolorem keyboard shortcut)
8. Works with multiple selection ranges
9. *NEW*: Does not leave trailing spaces

## Install

### Package Control

The easiest way to install this is with [Package Control](http://wbond.net/sublime\_packages/package\_control).

 * If you just went and installed Package Control, you probably need to restart Sublime Text 2 before doing this next bit.
 * Bring up the Command Palette (Command+Shift+p on OS X, Control+Shift+p on Linux/Windows).
 * Select "Package Control: Install Package" (it'll take a few seconds)
 * Select CthulhuDolorem when the list appears.

Package Control will automatically keep Git up to date with the latest version.

### Manual Install for ST3

1. Open the sublime text command pallete, and **Preferences: Browse Packages**
2. Checkout the ST3 branch of this repo in there
3. Restart ST3

Report bugs here, and I will do my best to repair them (or better still - make the fix, and send me a pull request).

---

If you have some problems or improvements with it, contact me via GitHub.

Also, any contributions of further gibberish to add to the mix are appreciated.