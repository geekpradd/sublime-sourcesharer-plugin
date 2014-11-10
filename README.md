#Sublime Text Source Sharer Plugin

This is a Sublime Text Plugin to directly share source code on the Internet. This uses [SourceSharer](http://www.sourcesharer.hol.es) which is a Web Platform created by me to share source code easily with others by just giving the link.


##Installation

To install this Plugin, search for 'Source Sharer' on Package Control which is the preferred distribution network of Plugins for developers uing Sublime Text. You can install Package Control from this link: [http://sublime.wbond.net](http://sublime.wbond.net)

Alternatively if you can't install Package Control for some reason, You can download [this zip](https://github.com/geekpradd/sublime-sourcesharer-plugin/archive/v1.1.0.zip) file and extract the content folder to C:\Users\USERNAME\AppData\Roaming\Sublime Text 3\Packages on Windows and reload Sublime Text 3 for the Plugin to start.

For Mac OSX, navigate to /Users/{user}/Library/Application Support/Sublime Text 3/Packages and paste the contents of the zip there and reload Sublime Text 3.

For Linux, navigate to ~/.config/sublime-text-3 from the terminal and paste the folder in the zip there and reload Sublime Text 3.
##Usage

To use this plugin, use the shortcut key- Ctrl+Alt+S or Click on SourceSharer in the Menu Bar and click Share Source Code

Once the plugin is started, the code of the current working file will be sent to our servers and saved in our MySQL Databases and the result link will be copied to the clipboard. To share this code with others, simply share the resultant link with others and ask them to open it in their browser of choice.

##About

This Plugin is developed using Python and Sublime Plugins API for Sublime Text. The Back end service is created using PHP 5.3, MySQL, jQuery and HTML5.

This Plugin supports Python, Java, C/C++, Haskell, Go, Ruby, LISP, Scala and Javascript code files.

Created By Pradipta. Copyright 2014

