# Softbody-LOVE
A softbody experiment using LOVE2D

# LOVE2D

To get started go to the following:
https://love2d.org/wiki/Getting_Started

## Mac OS X
On Mac OS X, a folder or .love file can be dropped onto the love application bundle. On the Mac Terminal (command line), you can use love like this (assuming it's installed to the Applications directory):

`open -n -a love "~/path/to/mygame"`
However, the above method will not output printed text to the terminal window. To do that, you will need to execute the love binary inside the application bundle directly:

`/Applications/love.app/Contents/MacOS/love ~/path/to/mygame`
You can set up an alias in your Terminal session to call the binary when you use love by adding an alias to your ~/.bash_profile.

Open the file with

`open -a TextEdit ~/.bash_profile`
You may have to run

`touch ~/.bash_profile`
first if the file does not yet exist.

Then paste in the following code and save the file:

# alias to love

`alias love="/Applications/love.app/Contents/MacOS/love"`
Now you can call love from the command line like Linux and Windows:

`love "~/path/to/mygame"`
