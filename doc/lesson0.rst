===============
Lesson 0: Setup
===============

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
  boxes, or just close the assocated windows if they pop up.

Test the Python Installation
----------------------------

Now let's test out the Python interpreter we just installed by
performing the following steps.

- After installation is complete, search for the newly-installed
  ``Anaconda Powershell Prompt`` program in the start menu and run it.
  A window with a command prompt like this should show up::

    (base) PS C:\Users\Username>

  This command prompt allows you to run Windows programs and execute
  system commands by typing the name of the program or command at the
  prompt.
  
- Start the Python interpreter program by typing ``python`` (the name
  of the Python interpreter program) at the Powershell prompt,
  followed by the ``<Enter>`` key.  When the interpreter starts up and
  is ready to accept Python commands, it will present you with a
  Python prompt that looks like this::

    >>>

- At this point, you can type Python commands at the prompt to execute
  them, one line at a time.  For example, typing::

    print("hello world")

  followed by ``<Enter>``, executes a Python command to print out the
  text "hello world" to the screen.

- Exit the Python interpreter by typing ``exit()`` followed by ``<Enter>``.

- Exit the Windows Powershell by typing ``exit`` followed by ``<Enter>``.

Create a Folder for Python Code Development
-------------------------------------------

Next, we will create a folder to hold the Python programs we will
create in this course.

- Open the Windows ``File Explorer`` by clicking on the file folder
  icon on the Windows taskbar at the bottom of your screen, or search
  for ``File Explorer`` in the start menu and run it.
  
- Browse to your ``Documents`` folder in the file explorer.

- Right-click in the empty area of the file explorer window and select
  the ``New->Folder`` option from the pop-up context menu to create
  new folder under ``Documents``.  Change the name of the folder from
  ``New folder`` (this text will be highlighted) to ``Python101``.

Install VSCode
--------------

We will use the VSCode plain-text editor and integrated development
environment (IDE) to edit and run Python programs.  This software can
be installed by following these steps:

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

Now we will configure VSCode for Python development as follows:

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

If you've gotten this far, then congratulations -- you have
successfully written and run your first Python program.

Install Git
-----------

The next step is to install the ``Git`` version control system.  This
software tool helps keep track of changes made to source code and
makes it easy to pull down source code from online code repositories.
We will use it to pull down code to support our ``Py101`` lessons.

- Download the latest ``64-bit Git for Windows Setup`` program from
  the `Git web site <https://git-scm.com/download/win>`_.

- Run the ``Git-2.42.0-64-bit.exe`` installer that you just downloaded.

- Click ``yes`` to allow the installer to make changes to your
  computer and accept the license agreement.

- Take the default installation options **except for the default
  editor used by Git**.  At this prompt, choose the ``Use Visual
  Studio Code as Git's default editor`` option.

Pull Down the Py101 Support Code
--------------------------------

Before we can start our lessons, we need to pull down some supporting
code from our ``Py101`` course web site.

- Open the Windows ``File Explorer`` by clicking on the file folder
  icon on the Windows taskbar at the bottom of your screen, or search
  for ``File Explorer`` in the start menu and run it.
  
- Browse to your ``Documents/Python101`` folder in the file explorer.

- Right-click in the empty area of the file explorer window and select
  the ``Show more options -> Open Git GUI here`` option from the
  pop-up context menu.

- Now choose ``Clone Existing Repository``.

- Type ``https://github.com/codecraftingacademy/py101.git`` in the
  ``Source Location`` box.

- Type ``py101`` in the ``Target Directory`` box.

- Click the ``Clone`` button to pull down the source code from GitHub.

- Close the ``GitGUI`` application.

- You should now see a ``py101`` folder inside your ``Python101`` directory.

Please don't move, edit or place any extra files inside the ``py101``
folder.  This folder is reserved for code downloaded from the
``Py101`` web site that will be used in our lessons.


