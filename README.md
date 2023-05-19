
# Sublime Text Syntax Highlighting Package for Autohotkey Language v2

### ***This is a work in progress. There are most likely some situations in which the highlighting is broken. I've improved it enough for myself to use it comfortably and it's very rare I run into anything but I do run into issues occasionally, which I fix. The biggest issue with this syntax definition, which is arguably not much of an issue depending on the color scheme you're using, is that many color schemes just don't support enough syntax tokens to fully take advantage of the syntax definition. This is remedied by using a comprehensive color scheme or just tweaking the color scheme you're using, which is incredibly easy to do within the application if you're using an up-to-date installation.***

#### ***Also, I intend to unify the syntax definition over time. Currently, I use some methods to do some things that I don't for others. The visible result isn't changed in any way by this, but I'm trying to build it in a way that recognizes the difference between, for example, an if-block and a while-block. The easy way is to just recognize whole blocks generically and recognize the differences between a line that starts an if-block and a line that starts with a while-block, which works just fine. But I want it to be smarter behind the scenes. The nature of the how sublime parses syntax definitions makes this very brain-hurty, but it is possible, and I've got it working in isolated cases. You can only make matches against one line at a time, so there's a lot of finagling involved.***
 
The Sublime Text Syntax Highlighting Package for Autohotkey Language v2 is a powerful tool that allows you to easily write and edit scripts in the Autohotkey language using Sublime Text. This package provides comprehensive syntax highlighting for all of the features and functions of Autohotkey language v2.

# Features
Comprehensive syntax highlighting for Autohotkey language v2.
Easy installation process with clear instructions.
Supports all of the latest features and functions of Autohotkey language v2.
Customizable color scheme to fit your preferences.

# Installation
To install the Sublime Text Syntax Highlighting Package for Autohotkey Language v2, simply follow these steps:

-Download the latest release from the Github repository.
-Open Sublime Text and go to "Preferences" > "Browse Packages".
-Extract the contents of the downloaded package into the "Packages" folder.
-Restart Sublime Text.
# Usage
Once you have installed the package, Sublime Text will automatically recognize and highlight the syntax of any file with the ".ahk" extension.

To customize the color scheme, go to "Preferences" > "Color Scheme" > "User" and add the following line:

```json
Copy code
{
  "name": "Autohotkey v2",
  "scope": "source.ahk",
  "settings": {
    "foreground": "your-chosen-foreground-color",
    "background": "your-chosen-background-color"
  }
}
```
Replace "your-chosen-foreground-color" and "your-chosen-background-color" with the values you prefer.

Keywords
Sublime Text Syntax Highlighting Package, Autohotkey Language v2, syntax highlighting, high-quality code, installation process, customization, color scheme, latest version, Sublime Text, Github repository.


