---
layout: page
title: Setup
root: .
---

1. Make a DATASCHOOL folder. Please make it inside your 'home' folder (which is named with your ident). For example: 

    Folder location on **windows**:

    <a href="{{ page.root }}/fig/folder-pc.JPG">
      <img src="{{ page.root }}/fig/folder-pc.JPG" alt="Folder location and path for pc" />
    </a>

    Folder location on **Mac**:

    <a href="{{ page.root }}/fig/folder-mac.png">
     <img src="{{ page.root }}/fig/folder-mac.png" alt="Folder location and path for mac" />
    </a>

    You need to download some files to follow this lesson:

2. Download [data-shell.zip]({{ page.root }}/data/data-shell.zip) and move the file to your new DATASCHOOL folder.
3. Unzip/extract the file (ask your instructor if you need help with this step). You should end up with a new folder called **data-shell** in your DATASCHOOL folder.
4. Open a shell (you might want to make yourself a shortcut!):

    **Windows:** Click on your search 'circle', search for 'Git Bash', open the desktop app. This is your shell. 
    
    **Mac:** Go to Finder > Applications > Utilities > Terminal. 'Terminal' is your shell. 
    
5. Within your shell, type `cd`, then press the Enter key. That last step will make sure you start with your home folder as your working directory.

In the lesson, you will find out how to access the data in this folder.  

> ## Where to type commands: How to open a new shell
> The shell is a program that enables us to send commands to the computer and receive output. It is also referred to as the terminal or command line.
>
> Some computers include a default Unix Shell program. 
> The steps below describe some methods for identifying and opening a Unix Shell program if you already have one installed. 
> There are also options for identifying and downloading a Unix Shell program, a Linux/UNIX emulator, or a program to access a UNIX server. 
>
> If none of the options below address your circumstances, try an online search for: UNIX shell [your computer model] [your operating system].
>
>
> ### Windows
> Computers with Windows operating systems do not automatically have a Unix Shell program installed.
> In this lesson, we encourage you to use an emulator included in Git for Windows, 
> which gives you access to both Bash shell commands and Git. 
>
> Once installed, you can open a terminal by running the program Git Bash from the Windows start menu.
>
> Other solutions are available for running Bash commands on Windows. 
> There is now a Bash shell command-line tool available for Windows 10. 
> Additionally, you can run Bash commands on a remote UNIX computer or server from your Windows machine. 
> This can be done through a Secure Shell (SSH) client.  
> See the references below for instructions on using the Windows 10 command-line tool, or installing and 
> using a UNIX/Linux emulator.
>
> #### Reference
> * [Git for Windows](https://git-for-windows.github.io/)
> * [How to Install Bash shell command-line tool on Windows 10](https://www.windowscentral.com/how-install-bash-shell-command-line-windows-10)
> * [Install and Use the Linux Bash Shell on Windows 10](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/)
> * [Using the Windows 10 Bash Shell](https://www.howtogeek.com/265900/everything-you-can-do-with-windows-10s-new-bash-shell/)
> * [Using a UNIX/Linux emulator (Cygwin) or Secure Shell (SSH) client (Putty)](http://faculty.smu.edu/reynolds/unixtut/windows.html)
>
> ### Mac OS
> For a Mac computer, the default Unix Shell is Bash,
> and it is available via the Terminal Utilities program within your Applications folder.
>
> To open Terminal, try one or both of the following:
> * Go to your Applications. Within Applications, open the Utilities folder. Locate Terminal in the Utilities folder and open it.
> * Use the Mac ‘Spotlight’ computer search function. Search for: `Terminal` and press <kbd>Return</kbd>.
>
> #### Reference 
> [How to Use Terminal on a Mac](http://www.macworld.co.uk/feature/mac-software/how-use-terminal-on-mac-3608274/)
>
> ### Linux
> The default shell for Linux operating systems is usually Bash.
> On most versions of Linux, it is accessible by running the [(Gnome) Terminal](https://help.gnome.org/users/gnome-terminal/stable/)
> or [(KDE) Konsole](https://konsole.kde.org/)
> or [xterm](https://en.wikipedia.org/wiki/Xterm),
> which can be found via the applications menu or the search bar.
> If your machine is set up to use something other than bash, you can run it by opening a terminal and typing `bash`.
{: .callout}
