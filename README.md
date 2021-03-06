## HTML Button

[https://classroom.github.com/a/xynRBdog](https://classroom.github.com/a/xynRBdog)

## While Array Practice

[https://classroom.github.com/a/9kCPfNnS](https://classroom.github.com/a/9kCPfNnS)

## Array Problem

[https://classroom.github.com/a/Vbz4MkyM](https://classroom.github.com/a/Vbz4MkyM)

## Array Practice

[https://classroom.github.com/a/qN3knGAY](https://classroom.github.com/a/qN3knGAY)

## Assignment-6-arrays

[https://classroom.github.com/a/H9QOQ4lH](https://classroom.github.com/a/H9QOQ4lH)

## Loop Practice

[https://classroom.github.com/a/evYSoK0i](https://classroom.github.com/a/evYSoK0i)

## Assignment 5 - Loops

[https://classroom.github.com/a/5OS6ZciI](https://classroom.github.com/a/5OS6ZciI)

### Ryder

[https://classroom.github.com/a/YMxW0Rna](https://classroom.github.com/a/YMxW0Rna)

### Kole

[https://classroom.github.com/a/3Eds6YHl](https://classroom.github.com/a/3Eds6YHl)

### Emma

[https://classroom.github.com/a/q8yTxjCE](https://classroom.github.com/a/q8yTxjCE)

### Phoenix

[https://classroom.github.com/a/B2st9LKb](https://classroom.github.com/a/B2st9LKb)

### Jeremiah

[https://classroom.github.com/a/GP2cYSXd](https://classroom.github.com/a/GP2cYSXd)

### Sam

[https://classroom.github.com/a/xvOj0N-M](https://classroom.github.com/a/xvOj0N-M)

### Assignment 4

[https://classroom.github.com/a/zf0oJ3Mo](https://classroom.github.com/a/zf0oJ3Mo)

### Assignment 3

[https://classroom.github.com/a/Jyw-Awhw](https://classroom.github.com/a/Jyw-Awhw)

### Assignment 2

[https://classroom.github.com/a/R84K4auk](https://classroom.github.com/a/R84K4auk)

### Supplement
[https://classroom.github.com/a/fIN10Nv4](https://classroom.github.com/a/fIN10Nv4)


### Introduction

It's time to install all of the things! It's here we'll show you all the apps
you'll want to use that will be helpful through the duration of the course.

### Install Chrome

#### Instructions
1) [Download](https://www.google.com/intl/en/chrome/browser/)

#### Why?

Chrome will be your primary development browser. Chrome is fast and efficient.
Chrome's developer tools (right click on an a page and select "Inspect Element")
are tremendously powerful and helpful for web development.

### Locate your Terminal

The Terminal is one application you can use to access the command line for your system. As a developer, you'll be using the command line frequently. We will install a better alternative to Terminal below, but we need to use Terminal to help us get started, first.

#### Instructions

1) Using Finder, navigate to Applications
2) Double-click on Utilities
3) Double-click on Terminal

Use the resulting window to execute the terminal commands as instructed below.

### Install Apple Xcode Command Line Tools

#### Instructions

Note that the installation of command line tools can take a bit of time.

1) Install the command line tools by entering the following command into your terminal
xcode-select --install
If the install fails, visit the [Apple Developer Tools
site](https://developer.apple.com/downloads/index.action) to download and
install "Command Line Tools OS X".

2) *Restart your computer*.

3) To verify that the install was successful, enter the following command into your terminal
xcode-select -p
You should see the following returned
/Library/Developer/CommandLineTools

#### Why?

Installation of many common Unix-based tools requires a GCC compiler. The Xcode Command Line Tools include a GCC compiler.

### Install Homebrew

#### Instructions

1) Run this command in the terminal
ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/install/master/install)"
ZOMG it's a Ruby script! It will take care of installing Homebrew for you.

2) To verify successful installation, run in your terminal
brew doctor
and you should see
Your system is ready to brew.
#### Why?

[Homebrew](http://brew.sh/) is a package management system that simplifies the installation of software.

### Install iTerm2

#### Instructions

1) [Download](http://iterm2.com/downloads)

2) Set iTerm to Reuse Previous Session's Directory by opening Iterm, and going to Iterm -> Preferences -> Profiles -> General -> Working Directory and choosing "Reuse previous session's directory".

*Note: You should now use iTerm instead of terminal for everything.*

#### Why?

The built in Terminal.app is great, but iTerm2 has some neat features that you
will make your life as a developer easier.
You can use either interchangeably for accessing the command line, but we recommend using iTerm2 from here on out.
Once installed, use iTerm2 for all command line or terminal commands below.

### Install Oh My ZSH

#### Instructions
1) Install it by running the following command in your command line interface
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
2) Verify that zsh is the default shell by going to to system preferences -> Users & Groups -> click the lock -> enter your password -> right click on your account -> hit advanced options -> verify your login shell is /bin/zsh -> if not, change it and restart your computer.

3) Finish the Oh My ZSH installation by restarting iTerm. Be sure to completely quit iTerm by using cmd + q and relaunch the application.


#### Why?

[Oh My ZSH](https://github.com/robbyrussell/oh-my-zsh) will make working in your
terminal much more enjoyable. It will configure a lot of things for you, such as
auto-completion and awesome colors. As a developer, you'll spend lots of quality time in your terminal, so it's a
good idea to take advantage of tools that make it easier and more fun to use.
### Install Atom

*  Download [atom](https://atom.io/)

### Getting Atom Set Up

#### Recommended Packages

*  Monokai Theme - sweet looking syntax theme
*  File Icons - will give you nice looking file icons

### Basic Keyboard Shortcuts

### Moving within a file
- *Move to the cursor to the border of the file* cmd + arrow key
- *Move the cursor word-by-word:* opt + → and opt + ←

### Opening files and moving between tabs
- *Open a file by name:* cmd + p, type in the name of the file, and press return.
- *Switch to a different open tab:* opt + cmd + → and opt + cmd + ←

### Highlighting
- *The whole file:* cmd + a
- *Highlighing multiple lines:* cmd + l will highligh one line. If you keep hitting l, more lines will be highlighted underneath!

### Modifying your code
- *Commenting:* cmd + / will comment out the current line. If a block of code is highlighted, then the whole block will be commented. Repeat action again to uncomment code.
- *Tabbing:* tab will tab your current line. If a block of code is highlighted, then the whole block will be tabbed. To un-tab press tab + shift.
- *Move current line up and down:* cmd + ctrl + ↑ and cmd + ctrl + ↓
- *Select the next word that's the same as the current word:* cmd + d (repeated however many times you want) will select the next word(s) that match the word your cursor is currently on - and create a cursor on each one when you start typing!

### External Resources
- [Atom Cheat Sheet](http://d2wy8f7a9ursnm.cloudfront.net/atom-editor-cheat-sheet.pdf)
- [Giant "Using Atom" Documentation](https://atom.io/docs/v0.188.0/using-atom-editing-and-deleting-text)

#### Why?

[Atom](https://atom.io/) is a text editor that's modern, approachable, yet hackable to the core—a tool you can customize to do anything but also use productively without ever touching a config file.


### Set Atom as your default editor

#### Instructions

1) Open Atom and click the "Atom" menu, then select "Install Shell Commands."

**2) Run the following command on the command line
>>>echo "export EDITOR=\"/usr/local/bin/atom --wait\"" >> ~/.zshrc

**3) Verify that this step was successful. On your command line, go to your root directory by running
>>>cd ~

**and opening up the .zshrc file with
>>>atom .zshrc

At the bottom of the file, you should see:
export EDITOR="/usr/local/bin/atom --wait"
#### Why?

We want to ensure that our terminal opens up Atom by default whenever an editor is needed.

### Install chruby

1) First, we have to check that a conflicting library is not in place. Ruby Version Manager, or RVM for short, is an alternative to chruby that you may have installed in the past. 

**Let's check that RVM is not installed by running the following command:
>>>rvm notes

**You should get
zsh: command not found: rvm


**If you do not get the expected output, uninstall RVM by running
>>>sudo rvm implode

2) We also need to check that we don't have another problematic application, known as MacPorts. This can cause conflicts and configuration issues with homebrew. 

**Check that MacPorts are not installed by running
>>>port help

**You should get
zsh: command not found: port

If you do not get the expected output, you can uninstall MacPorts by following [this guide](https://guide.macports.org/chunked/installing.macports.uninstalling.html).

**3) Install Chruby by running in your terminal
brew install chruby

**4) Enable Auto-switching current Ruby versions by running the following two commands
echo "source /usr/local/share/chruby/chruby.sh" >> ~/.zshrc
echo "source /usr/local/share/chruby/auto.sh" >> ~/.zshrc

**5) Verify that this step was successful. On your command line, go to your root directory by running
>>>cd ~
and opening up the .zshrc file with
>>>atom .zshrc

At the bottom of the file, you should see
source /usr/local/share/chruby/chruby.sh
source /usr/local/share/chruby/auto.sh
#### Why?

[chruby](https://github.com/postmodern/chruby) allows you to switch between
different versions of Ruby. Thus, you'll be able to work on multiple projects requiring different ruby versions.

### Install Ruby versions

**1) Install the Ruby version installer, [ruby-install](https://github.com/postmodern/Ruby-install#readme) with the command below.
brew install ruby-install

2) Install Ruby 2.4.5
ruby-install ruby 2.4.5
3) Set Ruby 2.4.5 as your default Ruby
echo "ruby-2.4.5" > ~/.ruby-version
4) Close iTerm and reopen it in order for these changes to take effect. Then run
chruby
You should see
* ruby-2.4.5
5) This last step will help you avoid issues in future assignments. Run:
gem install bundler
Note that in the video above, versions may differ. Like other modern software, different versions of the ruby programming language will be released from time to time. Where there is a conflict, rely on the written instructions to help you determine which version you should use.

#### Why?

You'll want a stable recent version of Ruby to develop with!

### Congrats! You're done with the core installation requirements!

mkdir ~/assignments

cd assignments

atom .

hello-world.rb

```
puts "hello world!"
```

ruby hello-world.rb


