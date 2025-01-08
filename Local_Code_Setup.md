# Using Python without Codespaces

While using Codespaces has it's advantages, if you are somewhere with an unstable internet connection, it may not be the best choice. This guide will teach you how to install and use an alternative to Codespaces on your own computer. 

This process is also slightly different depending on what operating system you use (Windows, Mac, ect.), so make sure to follow only the instructions for your operating system.

---

## Windows
### Installing Python

1. Go to the [Python download page for Windows](https://www.python.org/downloads/windows/)
2. Find the newest stable version on the left hand side of the page. At the time of writing, that is *Python 3.13.1*
3. Click on the download link for the Windows installer. 
    - If your computer is older it may only support 32-bit programs, so you would need to download the 32-bit version
    - To check whether you need the 32 or 64-bit installer, go to your computer's search bar and type "about",
    click "About your PC" and look under system type.
4. Once the installer is downloaded, run it.
5. Check the box that says "Add python.exe to PATH" and click "Install Now".
6. Accept any changes it asks to make to your system.
7. Once it's done with that, Click on the "Close" button in the bottom right corner.

Python should now be installed on your system. You can verify that everything worked correctly by
1. Opening your command prompt
    - Type *cmd* in your computer's seach bar
2. Type `py --version` and press enter.
    - If everything work correctly, it should display the version of python you installed.

### Installing an IDE

An Integrated Development Environment (IDE) is a program that facilitates coding, like Codespaces.

There are many different IDEs which have many different features, however My IDE of choice is VSCode, which works particularly well on windows machines. I will guide you through installing VSCode, however you can change IDE at any time so feel free to experiment around.

1. Go to the [VSCode website](https://code.visualstudio.com/)
2. Click "Download for Windows"
3. Once the installer is downloaded, run it.
4. Agree to the terms and conditions and click next.
5. The defaults on the next prompt are fine, however if you want VSCode to appear on your desktop make sure to check the "Create a desktop icon" before clicking next.
6. Finally click install and wait for it to finish. The installation should only take about a minute.
7. Once it is done, check the "Launch Visual Studio Code" box and click finish.

## Mac
### Installing Python

1. Go to the [Python download page for Mac](https://www.python.org/downloads/macos/)
2. Find the newest stable version on the left hand side of the page. At the time of writing, that is *Python 3.13.1*
3. Click on the download link for the *macOS 64-bit universal2 installer*. 
4. Once the installer is downloaded, run it.
5. Click the continue button on the Introduction page.
6. Click the continue button on the Read Me page.
7. Agree to the liscence terms.
8. Click the install button.
9. The installer will ask for permission to install new software, for this you will need a macOS user name with Administrator priviledges.
10. When the installation is complete, it will bring you to a summary page which you can close.

Python should now be installed on your system. You can verify that everything worked correctly by
1. Opening your terminal
    - Press *Cmd* + *Space* to open spotlight.
    - Search for terminal
2. Type `python --version` and press return.
    - If everything work correctly, it should display the version of python you installed.

### Installing an IDE

An Integrated Development Environment (IDE) is a program that facilitates coding, like Codespaces.

There are many different IDEs which have many different features, however My IDE of choice is VSCode. I will guide you through installing VSCode, however you can change IDE at any time so feel free to experiment around.

1. Go to the [VSCode website](https://code.visualstudio.com/)
2. Click "Download Mac Universal"
3. Once it is done downloading you should see a VSCode zip file in you brower downloads.
4. Click the downloaded file to extract the zip file.
5. Navigate to your downloads folder in finder.
6. Run the "Visual Studio Code" application file.
4. Agree to the terms and conditions and click next.
5. The defaults on the next prompt are fine, however if you want VSCode to appear on your desktop make sure to check the "Create a desktop icon" before clicking next.
6. Finally click install and wait for it to finish. The installation should only take about a minute.
7. Go to the finder icon in your task bar and create a new finder window.
8. Navigate to your applications folder in this new window.
9. Drag the Visual Studio Code application into your applications folder.
10. Now you can Launch Visual Studio Code from your launchpad.

## VSCode setup
### Extentions

there are a few extensions that you should make sure are installed in VSCode to make programming as smooth as possible.

1. Press *Ctrl* (or *Cmd*) + *Shift* + *X* or click on the Extentions tab on the left.
2. Search for "Python" in the extensions search bar.
3. Click install on that extention.
4. Do the same thing with the extentions "Pylance" and "Jupyter".

### Cloning Repositories

1. Go to your GitHub account and find the repository you forked.
1. Press *Ctrl* (or *Cmd*) + *Shift* + *P*.
2. Search for and click on "Git: Clone".
3. 
