# Getting Started
Welcome to the OldDigibox development team. Here, we develop projects such as Sky Web EPG,
Network, OldDigibox.GitHub.IO, Sky Web Games, Sky Web Active, EPG Background Audio Emulator, 
Emubox and OldDigibot. The documents in this repository will show you how to develop for these
projects, and how to make use of our resources.

## Step 1: Install Visual Studio
For all of our projects, you need Visual Studio Community 2019, which you can get at https://visualstudio.microsoft.com/downloads/. We do NOT use Visual Studio Code
due to its lack of Git GUI. In the Visual Studio Installer, you need to select *Desktop Development for C++*, *ASP.NET and web development*, and if you want, *Node.js development*.

## Step 2: Install Git
Now, we need to install Git. You can get it here: https://git-scm.com/downloads

# Developing with Visual Studio and its Git Integration
## Cloning Our Repositories
To clone our Repositories, open Visual Studio, and on the start window, select "Clone or check out code" and enter the path of the repository. If it is private, you may be asked for your
GitHub username and/or E-Mail & password. To make sure you are already signed in to GitHub on Visual Studio, go on the View tab and open the Team Explorer. From there, go to Settings,
Global Settings, and enter your GitHub User Name and Email Address. Keep all other settings the same, except for Default Repository Location if you wish to change it. Now, you can edit code.
You can open files in the repository using the Solution Explorer.

## Publishing Changes You've Made
Now, it's time to publish the changes you made. Go back to the Team Explorer and click the Home icon. Now go to Changes, and enter your commit message. Now, you need to describe
what changes you made; however, don't write them in past tense e.g. *Changed this to that.* Also don't end them with full-stops/periods. You need to write them as if you're
about to do it, e.g. *Change this to that.* Select Commit All, and head over to Sync. Here, you can click Push and it will upload your changes to the repository. If it worked, you should receive the
notification from the `#developer-den` channel on the OldDigibox Discord server.

## Updating With Other Developers' Changes
What if there is a commit that has been pushed, that you want on your local repository? Just Pull it. On the Team Explorer, click the Home icon, head over to Sync and select Pull.

***MAKE SURE YOU COMMIT ANY UNCOMMITTED CHANGES FIRST!***
