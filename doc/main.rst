Status
======

This project is a work in progress.  Please check back for updates.

Windows Setup
=============

Install Python
--------------

The first step to programming in Python is to install the Python
interpreter and supporting packages by following the instructions
below.

- Browse to the `Anaconda Web Site
  <https://www.anaconda.com/download#downloads>`_.

- Download the Python 3.11 (or later) ``64-Bit Graphical Installer``.

- Run the downloaded ``Anaconda3-2023.07-2-Windows-x86_64.exe`` file
  and install it for ``All Users`` in the default location and
  register it as the system Python.  Uncheck the ``Launch Anaconda
  Navigator`` and ``Getting Started with Anaconda Distribution``
  boxes, or close the assocated windows if they pop up.

- After installation is complete, search for the newly-installed
  ``Anaconda Powershell Prompt`` program in the start menu and run it.
  A window with a prompt like this should show up::

    (base) PS C:\Users\Username>

  This prompt allows you to run Windows programs and execute system
  commands by typing the name of the program or command at the
  Powershell prompt.
  
- Start the Python interpreter program by typing ``python`` at the
  Powershell prompt, followed by the ``<Enter>`` key.  When the
  interpreter is ready to accept Python commands, it will present you
  with a prompt that looks like this::

    >>>

- At this point, you can type Python commands at the prompt to execute
  them, one line at a time.  For example, typing::

    print("hello world")

  followed by ``<Enter>``, executes a Python command to print out the
  text "hello world" to the screen.

- Exit the Python interpreter by typing ``exit()`` followed by ``<Enter>``.

- Exit the Powershell by typing ``exit`` followed by ``<Enter>``.

Create a Folder for Python Code Development
-------------------------------------------

- Open the ``Anaconda Powershell Prompt`` as described above, but this
  time don't start the Python interpreter.

- At the Powershell prompt (not the Python prompt), type::

    mkdir Documents/Python101

  which will create a new folder underneath your Windows ``Documents``
  folder.
  
- Open the Windows file manager and browse to your ``Documents``
  folder.  You should see an empty ``Python101`` folder inside.  This
  is where we will keep the programs you create in this course.

Install VSCode
--------------

The VSCode plain-text editor and integrated development environment
(IDE) can be installed by following these steps:

- Browse to the `VSCode web site <https://code.visualstudio.com/download>`_.

- Click on the ``x64 User Installer for Windows 10/11`` button to
  download the installer.

- Run the ``VSCodeUserSetup-x64-1.81.1.exe`` installer program you
  just downloaded and install with the default options.

- After installing, VSCode can be started by searching for ``Visual
  Studio Code`` in the start menu and running that application.

Note that any plain-text editor (even the Windows ``Notepad``
application) can be used to edit Python programs, but a specialized
IDE generally makes program development easier and more productive.

Set up VSCode for Python Development
------------------------------------

- After launching VSCode, click the gear icon (aka ``Manage``) in the
  bottom-left corner and then click on ``Extensions``.

- Type "python" in the search box of the ``Extensions: Marketplace``.

- Choose ``Install`` for the ``Python`` extension from Microsoft and wait
  for it to finish installing.

- Now choose the ``View->Command Palette`` menu option, type
  ``Terminal: Select Default Profile`` in the search box, and then
  choose ``Command Prompt``.

- Now click the pages icon (aka ``Explorer``) in the top-left corner
  and then click on the ``Open Folder`` button.
  
- Browse into the ``Documents`` folder and select the ``Python101``
  folder you created earlier.

- Now click the ``Select Folder`` button and then click the ``Yes, I
  trust the authors`` button.

- Now select the ``File->New File`` menu option and then ``Python
  File``.

- Now you have a new (still untitled) plain-text document opened for
  editing.
  
- Type this text on line the first line of the file::

    print("hello world")

- Now let's save the file by selecting the ``File->Save`` menu option.

- Type ``hello`` in the ``File name`` box and then press the ``Save``
  button.

- Now let's try to run the program by clicking the "play" arrow icon
  in upper right corner.

  When you do this for the first time, you may see an error message
  about an invalid Python interpreter pop up in the lower-right corner
  of your screen.  If so, click the ``Select Python Interpreter``
  button, choose the "Conda" (or "Anaconda") Python interpreter (there
  is probably only one option), and then press the "play" arrow to try
  again.

- This time, you should see a terminal area pop up at the bottom of
  your VSCode window.  This terminal will show the shell command used
  to run your program (i.e. ``hello.py``) with the Python interpreter,
  followed by the output of your program (i.e. ``hello world``).

- If you've gotten this far, then congratulations -- you have
  successfully written and run your first Python program.
  
..
  - Now click the little gear icon (aka ``Manage``) next to the Python
    extension and then click on ``Extension Settings``.

  - Scroll down to find the ``Python->Terminal: Activate Environment``
    setting and uncheck the associated box.

