# Eso Code
![Eso Code icon](textures/icon.png?raw=true)

A small IDE designed for brainfuck and other esolang programming; name inspired by VS Code.

# Features
 - Basic code writing environment
 - Saving and loading source files
 - Compile esolang code to .exe files
 - Internal GCC compiler binaries included, no need to install anything yourself, everything this program needs is included in the download
 - Internal interpreter for testing code without having to compile
 - Macro support

P.S. The internal interpreter is a work in progress, it does not support input and can freeze with programs that are too large.

# How to install and run
To install, just pull this repo and run the .pyw file.

# Requirements?
The only requirements to use this IDE include the following:
 - Latest version of python

P.S. This may also work on older versions of python 3, but I have not tested them.

# Writing your first esolang program
When first opening Eso Code, you will be met with a startup screen asking for the target language. The default is brainfuck, but you can any one you like. (the only one programmed in right now is brainfuck)
Once you've selected your target language, simply hit continue.
This startup screen will also tell you if you have GCC installed, if you don't have it installed; there will be an error letting you know.

After you've set everything up, you are met with a blank text area. This is where you can either manually type in your code, copy and paste code from the internet, or load and save code from source files.

Once you have written your code, you might want to comment it. There is no specified comment indicator, as all characters that aren't brainfuck commands are discarded, so any plain text is treated as a comment. (This may depend on what esolang you are programming in, but for many this holds true)

Now that you have a fully fledged and documented masterpiece in the IDE, it's time to compile. Simply go to the file menu and hit the compile button. It will ask you for a location and name for the exe. Hit save, and its done!

If you want things to be a little easier, you can generate brainfuck code to easily pring strings. This option can be found in "Insert Macro" -> "Generate Print String".
In the generate print string menu, you can type any source text you want; once you're done, hit insert macro. (This only applies to certain esolangs like brainfuck)

# User Interface
![Main Interface](screenshots/main_interface.PNG?raw=true)

![Insert Macros](screenshots/insert_macro.PNG?raw=true)
