## Week #1:

### Setting up your development environment

#### The OS

If you're running OSX or any flavor of Linux, you're good.

If you're on windows, you have a bit of extra work since nothing runs in windows and I won't bother to give instructions for windows in any future lessons ;)  So you're going to have to set up a Virtual Machine running linux:
  - Download VirtualBox (or VMWare, though it isn't free)
  - Install Ubuntu Server

If you have some time to kill, you're welcome to learn Vagrant at this point.  It's a useful tool that helps with this step, but it's completely overkill for now.

#### The Editor

You're welcome to use whatever editor you want, though I highly recommend Sublime Text 3.  Atom and WebStorm are other decent options.

If you're using a virtual machine (per the previous section), I suggest mounting a directory from your VM to your local machine (Google is your friend here ;))

#### Install necessary software for this week

You're going to need to get familiar with console, as many things will be done from there, including (often) installing software.  Install the following if not already installed:

- If using OSX, install homebrew (this is a software package manager that is used to easily install many other tools)
- git
- node.js
- Create an account on github.com
  - Fork this repository (link at the top-right of the main page)
  - Clone the repository to your local machine
    - Open your console
    - Create a new directory somewhere
    - Type `git clone <path to your repository>`

#### Trial by fire (aka this week's actual programming tasks)

I strongly believe in learning to do something by actually doing tasks, as opposed to simply reading how things work.  So that being said:

- If you're not at all familiar with JavaScript syntax, start by going to codeacademy.com and do the first few JavaScript lessons
- Visit projecteuler.net
- Make an account
- Do the first 10 problems

You'll notice that there is a 'euler' directory nested under the "week-001" directory that you're in.  If you open that directory in your console and type:

    node . 1

It will execute the `.js` file `0001.js` for you.  The first 10 `.js` files you need are included in the `solutions` directory, along with some basic code and information about what you will need to learn to complete each problem.

Have fun!  :)