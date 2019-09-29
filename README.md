Sublime Tutor
==============

![Sublime Tutor Screenshot](https://raw.githubusercontent.com/jaipandya/SublimeTutor/gh-pages/images/screenshots/sublimetutor1.jpg)

         _______. __    __  .______    __       __  .___  ___.  _______
        /       ||  |  |  | |   _  \  |  |     |  | |   \/   | |   ____|
       |   (----`|  |  |  | |  |_)  | |  |     |  | |  \  /  | |  |__
        \   \    |  |  |  | |   _  <  |  |     |  | |  |\/|  | |   __|
    .----)   |   |  `--'  | |  |_)  | |  `----.|  | |  |  |  | |  |____
    |_______/   .___________.________ |.___________.|________|.________|
                |           |  |  |  | |           |/  __  \  |   _  \
                `---|  |----|  |  |  | `---|  |----|  |  |  | |  |_)  |
                    |  |    |  |  |  |     |  |    |  |  |  | |      /
                    |  |    |  `--'  |     |  |    |  `--'  | |  |\  \----.
                    |__|     \______/      |__|     \______/  | _| `._____|
                                                         FOR SUBLIME TEXT 3

Sublime Text 3 is a powerful and easy to use text editor. An ultra simple user
interface beautifully hides all the complexity behind. You can start using the
editor without knowing any details, which is great for beginners.

When I started using Sublime Text, I was a migrant from the world of TextMate
and Vim. While a lot of keyboard shortcuts and features were similar to
TextMate, some looked alien as well. Earlier, when I was learning Vim, I had
found vimtutor to be of great help. In my early days with Sublime, I was
looking for a similar solution which could interactively teach new shortcuts
inside the editor itself.

This tutorial is inspired from classic vimtutor. You will get to learn
some handy shortcuts to work with Sublime Text 3. By the end of this tutorial,
you would be familiar with ST's most important and frequently used shortcuts
and features.

The tutorial uses spaced repetition technique to make sure that your newly
acquired skills are well persisted.

Requirements
-------------

You have Sublime Text 3 installed on your system. If not, you can download it
from here: https://www.sublimetext.com/3. In case if you are on version 2, you
can clone this GIT repository on your system and follow the instructions in
`tutorial` directory inside. Some shortcuts and features discussed would be
ST3 only, but you'd know about it then.

Having said that, there is no reason that you should be using Sublime Text 2. A
lot of improvements have been made since the version 2 and the latest version
is stable enough to do most of the things. Unless, your life depends on a plugin
that is only supported by ST2. I can't help you then.


## Installation

### By Package Control

1. Download & Install **`Sublime Text 3`** (https://www.sublimetext.com/3)
1. Go to the menu **`Tools -> Install Package Control`**, then,
   wait few seconds until the installation finishes up
1. Go to the menu **`Tools -> Command Palette...
   (Ctrl+Shift+P)`**
1. Type **`Preferences:
   Package Control Settings – User`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
   add the following setting to your **`Package Control.sublime-settings`** file, if it is not already there
   ```js
   [
       ...
       "channels":
       [
           "https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json",
           "https://packagecontrol.io/channel_v3.json",
       ],
       ...
   ]
   ```
   * Note,
     the **`https://raw...`** line must to be added before the **`https://packagecontrol...`**,
     otherwise you will not install this forked version of the package,
     but the original available on the Package Control default channel **`https://packagecontrol...`**
1. Now,
   go to the menu **`Preferences -> Package Control`**
1. Type **`Install Package`** on the opened quick panel and press <kbd>Enter</kbd>
1. Then,
search for **`SublimeTutorial`** and press <kbd>Enter</kbd>
1. Restart Sublime Text

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


Getting Started
----------------

If you haven't already, install Sublime Tutor using the installation steps
given above.

Once Sublime Tutor is installed, press <kbd>Ctrl</kbd>+<kbd>Option</kbd>+<kbd>K</kbd>
keyboard shortcut to open this file in Sublime Text. Another option is to go to
`Help > Sublime Tutor` menu option to open this.

Via Command Palette:

1. <kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> to get the command palette in
   front.
2. Type `Sublime Tutor`, select the first command that comes up to start the
   interactive guide.


Symbols Used in this guide
---------------------------

* `Cmd` – <kbd>Command</kbd> Key
* `Ctrl` - <kbd>Control</kbd> Key
* `Option` – <kbd>Option</kbd> Key
* `Shift` – <kbd>Shift</kbd> Key
* `Esc` – <kbd>Escape</kbd> Key
* `Return` – <kbd>Return</kbd> Key
* `Delete` – <kbd>Delete</kbd> / <kbd>Backspace</kbd> Key

[1]: https://git-scm.com/ "Git is a version control system"


Contributing
-------------

1. **Give feedback** -
   If you went through the course and think a particular thing can be done in
   a different way, you want a feature covered, or there was something that you
   specially liked, please let me know via a
   [tweet](https://twitter.com/jaipandya/) or
   [email](mailto:hello@jai.im?Subject=Feedback%20On%20Sublime%20Tutor)
2. **Issues** -
   Found an issue? Typo, error or a topic needs more details, please create an
   issue by going to https://github.com/jaipandya/sublimetutor/issues
2. **Pull request** -
   Are you comfortable with git? If you know solution to any of the issues
   listed above, fork the repository, make your changes and create a PR with
   your changes. Refer to the branches section below while making these changes.

### Branches

All osx platform related changes go in the `master` branch of this repository
while all windows / linux related changes go in `win/linux` branch.
