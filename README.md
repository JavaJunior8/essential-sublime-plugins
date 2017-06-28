# Essential Sublime Text Plugins for Full-Stack Developers
The creators of Sublime Text say it’s a text editor you’ll fall in love with and, having worked with it for almost a year now, I must say I completely agree with them. It has an untimed trial, and a licence for a single user costs $70. If you spend most of your day working with a text editor, I would say it’s a worthy investment!

What makes Sublime Text even better is its extensibility. So, here’s a look at the plugins that make an already wonderful editor truly Sublime.

### ```1. Package Control```

One way of installing Sublime Text plugins is by downloading files and copying them to the packages directory. However, you should go through that process exactly once, because there exists a plugin called Package Control: a package manager, enabling you to install other plugins without leaving Sublime Text. It’s like ```sh apt-get``` for Ubuntu, ```sh pip``` for Python and ```sh npm``` for node.js.

Follow the installation instructions here and you won’t have to install another plugin manually ever again.

To verify that it’s been correctly installed, press ```Ctrl/Cmd + Shift + p``` and type in ‘package control’ — you should be able to view a list of options.

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/1.png)

### ```2. Git```

These days, more often than not, you are going to work with a version control software, and the most popular VCS is Git. Are you tired of saving your text files and switching back to the terminal to run a few Git commands. Wouldn’t it be nice if you could execute Git commands from the text editor itself? Install the Git plugin and get more done in less time!

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/2.png)

### ``` 3. GitGutter```
Although you can run Git commands from within Sublime Text, why check the differences in a file from the last commit by running a separate command when you can view it in real time?

With GitGutter, you can see which lines have been added, deleted or modified in the gutter.

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/3.png)


### ```4. Emmet```

Emmet is a useful plugin that saves time by making you write less, thus increasing your productivity. Emmet is available for other text editors like Notepad++ and Eclipse.

There are a [lot of things](http://www.hongkiat.com/blog/html-css-faster-emmet/) that you can accomplish with Emmet, but I will just tell you my favorite here. Type ```sh html:5``` and press ```sh Ctrl/Cmd + e```, and it is expanded to a basic HTML 5 page template. Simple!

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/4.png)


### ```5. AllAutocompletet```

Sublime Text’s default autocomplete considers words that are present in the current file only. The AllAutocomplete plug-in, however, searches all open files to find matches while suggesting words.


![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/5.png)

### ```6. Terminal```

Just in case you want to open a terminal in the directory of your current file, this plugin can be of use. However, by default, it sets ```sh Ctrl/Cmd + Shift + t``` as the shortcut for opening the terminal, which is also the shortcut to open the last closed file. You should change either of the shortcuts to be able to use both functionalities!


![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/6.png)


### ```7. SublimeREPL```

This is probably the most useful plugin for programmers. SublimeREPL lets you run an interpreter of a range of languages (NodeJS, Python, Ruby, Scala and Haskell to name a few) right inside Sublime Text. Let us run a Python interpreter and see if it works. Perform some list checks and computed 48 raised to the power 100.

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/7.png)


### ```8. ColorPicker``` 
Usually, if you want to use a color picker you probably open Photoshop or GIMP and use the built-in color picker there. The ColorPicker plugin lets you use a color picker within Sublime Text! After installation, just press ```sh Ctrl/Cmd + Shift + c```.

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/8.png)

### ```9. MarkdownPreview``` 
Although many developers prefer to create Markdown files in the cloud (GitHub Gists, StackEdit, Markable), this is for the ‘old school’ writers who prefer to keep their files locally. Although MarkdownPreview is primarily to preview Markdown files, you can go one step further and install [MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing), which gives you proper color highlighting.

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/9.png)

### ```10. DocBlockr``` 
If you follow coding guidelines strictly, this is one plugin that makes your task easier. DocBlokr helps you in creating proper comments for your code, by parsing the functions, parameters, variables, and automatically adding the basic items. Start with “/**” and DocBlockr does the rest for you. For instance, check how DocBlockr makes my life easier by creating a format for me to fill based on my comment.

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/10.png)


### ``` 11. Todo​Review```

Simple: A SublimeText plugin for reviewing TODO (and other) comments within your code.

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/11.png)

### ``` 12. CSScomb```

Want to format your CSS with the click of a button so it is properly formatted per WordPress's coding standards? This is the appropiate plugin for do that.

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/14.png)

### ``` 13. SublimeLinter```

SublimeLinter is a plugin for Sublime Text 3 that provides a framework for linting code. Whatever language you code in, SublimeLinter can help you write cleaner, better, more bug-free code. SublimeLinter has been designed to provide maximum flexibility and usability for users and maximum simplicity for linter authors.

The documentation for SublimeLinter is divided into two sections: one for users, and one for developers who would like to create their own linter plugins.

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/13.png)

### ``` 14. SideBarEnhancements```

This plugin provides enhancements to the operations on Sidebar of Files and Folders for Sublime Text.

Move to trash
Clipboard
Open in browser
Copy the content of a file as data:uri base64
Close, move, open and restore buffers affected by a rename/move command
Copy as tags img/a/script/style
Duplicate
Preference to control if a buffer should be closed when affected by a deletion operation
Allows to display "file modified date" and "file size" on statusbar

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/12.png)

### ``` 15. Sublime SFTP```

Spend less time managing file transfers and more time coding. FTP, FTPS and SFTP support for Sublime Text 2 & 3 that is blazing fast, with smart features, flexible workflow options and top-notch support.

* Work off of a server – edit and manipulate files and folders
* Map a local folder to a remote folder
	- Publish files, folders, or just the changes since your last commit
	- Sync folders – up, down or both directions
	- Diff local vs. remote versions of a file
	- Other operations and options to help you get stuff done
* Password and SSH key auth with SSH agent support
* Persistent connections for performance	

![N|Solid](https://raw.githubusercontent.com/franvergara66/essential-sublime-plugins/master/images/15.png)


With this, we come to the end of our list of plugins to boost your productivity.