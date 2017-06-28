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
