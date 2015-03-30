# Windows Setup
How to set up a dev environment on Windows

### Environment Variables

Environment variables are essentially variables that are unique to your computer.  In a practical sense, an environment variable is what you can run from your command line.  If you want to run a command from your command line, it must be addded to the environment variables.

Read [this](http://www.itechtics.com/customize-windows-environment-variables/) article for a brief overview of how to manage your environemnt variables.  The easiest way to start is to use the manual method.  Later on, you can use third-party software.

Most development software that you install will require that you add its path to your system's or user's environment variables.

### Git

[Download](http://git-scm.com/download/win) and install Git.  Use all of the default settings EXCEPT the following:

When the option 'Adjusting your PATH environment' appears, select 'Use Git and optional Unix tools from the Windows Command Prompt'.  This will allow you to use some Unix commands, such as `ls` and `mkdir`.

Note: *This is an opinionated way of setting up your environment.  If you hav experience with the command line and a Windows dev environment, feel free to install to your liking.*


### Extra Goodies

#### Console 2

Console 2 is an alternate console for Windows.  It looks a little better and is more customizable than the default command line interface.  Check it out [here](http://sourceforge.net/projects/console/).
