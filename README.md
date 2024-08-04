[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15345365&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Prerequisites
Administrator Rights: Ensure you have administrative rights on your Windows 11 system to install software.
System Requirements: Check that your system meets the minimum requirements for running VS Code:
Operating System: Windows 7, 8, 10, or 11 (32-bit or 64-bit)
Memory: At least 1 GB of RAM (2 GB recommended)
Disk Space: At least 200 MB of free disk space
Steps to Download and Install Visual Studio Code
Open Your Web Browser:

Open your preferred web browser (e.g., Chrome, Edge, Firefox).
Go to the Visual Studio Code Website:

Navigate to the official Visual Studio Code download page: Visual Studio Code
Download Visual Studio Code Installer:

On the download page, click on the version suitable for Windows (usually, the website detects your OS and offers the appropriate version automatically).
Choose between the User Installer (recommended) or the System Installer if you need to install VS Code for all users on the system.
Run the Installer:

Once the download is complete, locate the installer file (usually in your Downloads folder) and double-click it to run.
If prompted by the User Account Control (UAC), click "Yes" to allow the installer to make changes to your device.
Accept the License Agreement:

Read through the license agreement. If you agree, check the box that says "I accept the agreement" and click "Next".
Select Destination Location:

Choose the directory where you want to install Visual Studio Code or leave it as the default location. Click "Next".
Select Additional Tasks:

You can choose to create a desktop icon, add "Open with Code" action to the context menu, and more. Select the options you prefer and click "Next".
Install:

Review your installation settings and click "Install" to begin the installation process.
The installer will copy the necessary files to your system.
Launch Visual Studio Code:

Once the installation is complete, you can choose to launch Visual Studio Code immediately by checking the "Launch Visual Studio Code" box and clicking "Finish".
Alternatively, you can open VS Code later from the Start menu or the desktop icon if you created one.
Initial Setup:

When you first run VS Code, you might be prompted to install additional components, such as language packs or extensions. Follow the on-screen instructions to set up your development environment.
Post-Installation Configuration (Optional)
Extensions: VS Code supports a wide range of extensions for various programming languages and tools. You can install extensions from the Extensions view (accessible from the sidebar or by pressing Ctrl+Shift+X).
Settings Sync: If you use VS Code on multiple devices, consider setting up Settings Sync to keep your settings, extensions, and keybindings in sync across devices.


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

Initial Configurations and Settings
Theme and Appearance:

Dark/Light Theme: Go to File > Preferences > Color Theme or use Ctrl+K Ctrl+T to choose a theme that suits your preference.
Icon Theme: Go to File > Preferences > File Icon Theme to select an icon theme that enhances the visual representation of files and folders.
Font and Editor Settings:

Font Size and Family: Adjust the font size and family in File > Preferences > Settings and search for Editor: Font Size and Editor: Font Family.
Line Height and Letter Spacing: Customize line height and letter spacing for better readability in the same settings menu.
Tab and Indentation Settings:

Tab Size: Set the tab size by searching for Editor: Tab Size in the settings.
Indentation: Configure indentation settings like Editor: Insert Spaces to use spaces instead of tabs.
Auto Save:

Enable auto-save by searching for Files: Auto Save in the settings and setting it to afterDelay or another preferred option.
Word Wrap:

Enable word wrap by searching for Editor: Word Wrap and setting it to on.
Minimap:

Toggle the minimap by searching for Editor: Minimap and configuring its visibility and size.
Line Numbers:

Enable or customize line numbers by searching for Editor: Line Numbers.
Settings Sync:

Enable Settings Sync to synchronize your settings, extensions, and keybindings across multiple devices. Go to File > Preferences > Settings Sync and follow the instructions to sign in and enable sync.
Essential Extensions
Language Support:

Python: Install the Python extension for linting, debugging, and IntelliSense.
JavaScript/TypeScript: The built-in support is good, but you might want to install additional extensions like ESLint for linting.
C++: Install the C/C++ extension for debugging and IntelliSense.
Java: Install the Java Extension Pack for comprehensive Java development.
Code Formatting:

Prettier: A popular code formatter that supports multiple languages.
ESLint: Linting and code style checking for JavaScript and TypeScript.
Version Control:

GitLens: Enhances the built-in Git capabilities with features like blame annotations, status bar integrations, and more.
Productivity:

Live Server: Launch a local development server with a live reload feature for static and dynamic pages.
Path Intellisense: Provides autocompletion for file paths.
Debugging:

Debugger for Chrome: Debug JavaScript code running in Google Chrome directly from VS Code.
Python: The Python extension also includes debugging capabilities.
Themes and Icons:

Material Theme: A popular theme with a variety of color schemes.
Material Icon Theme: A widely used icon theme for better file and folder representation.
Markdown:

Markdown All in One: Comprehensive support for Markdown, including preview, snippets, and linting.
Configuring Extensions
Configure Python:

After installing the Python extension, configure the interpreter by clicking on the interpreter selection in the status bar and choosing the appropriate Python environment.
Configure ESLint and Prettier:

Set up a configuration file (.eslintrc and .prettierrc) in your project root to define your coding standards and formatting rules.
Customize Keybindings:

If you have specific workflow preferences, customize your keybindings by going to File > Preferences > Keyboard Shortcuts or by editing the keybindings.json file.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   1. Activity Bar
Location: On the far left side of the window.

Purpose: The Activity Bar provides access to different views and sections of the editor. It contains icons for quick navigation between primary activities such as:

Explorer: For managing files and folders.
Search: For searching across files.
Source Control: For version control integration (e.g., Git).
Run and Debug: For running and debugging code.
Extensions: For managing and installing extensions.
The Activity Bar can be customized with additional views from installed extensions, and its icons can be rearranged or removed.

2. Side Bar
Location: Immediately to the right of the Activity Bar.

Purpose: The Side Bar displays the contents and functionality of the selected activity from the Activity Bar. For example:

Explorer: Shows a file tree of your project and lets you manage files and folders.
Search: Displays search results and allows for advanced search and replace operations.
Source Control: Shows version control status, changes, and actions.
Run and Debug: Provides controls for starting, stopping, and configuring debug sessions.
Extensions: Lists installed extensions and allows you to search for new ones.
3. Editor Group
Location: The central area of the window, occupying the majority of the screen space.

Purpose: The Editor Group is where you write and edit your code. It supports multiple editors in various layouts, such as:

Tabs: Each open file is represented by a tab. You can switch between tabs to work on different files.
Splitting: You can split the editor into multiple groups (columns or rows) to view and edit multiple files simultaneously.
Preview: VS Code can show a preview of a file when you single-click it in the Explorer, without opening a new tab until you start editing.
You can drag and drop files between different editor groups to organize your workspace as needed.

4. Status Bar
Location: At the bottom of the window.

Purpose: The Status Bar provides information about the current state of the editor and the active file. It includes:

File Information: Displays the current file's path, line number, column number, and language mode.
Git Branch: Shows the current Git branch and provides quick access to version control actions.
Errors and Warnings: Displays the count of errors and warnings in the current file or workspace.
Encoding and End of Line: Shows the current file's text encoding and line-ending format.
Feedback and Extensions: Includes icons for feedback and extensions that might add their own status indicators or actions.
The Status Bar is highly interactive, with many elements acting as buttons to quickly access related features or settings.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The Command Palette in Visual Studio Code (VS Code) is a powerful feature that provides quick access to various commands and functionalities within the editor. It allows users to execute commands, navigate the workspace, and manage settings without having to remember specific keyboard shortcuts or navigate through menus.

Accessing the Command Palette
Keyboard Shortcut: Press Ctrl+Shift+P (or F1) to open the Command Palette.
Menu Navigation: Go to the menu bar and select View > Command Palette.
Examples of Common Tasks Using the Command Palette
Search and Open Files:

Type >open file or simply start typing the name of the file you want to open. VS Code will suggest matching files in your workspace.
Change Theme:

Type >theme and select Preferences: Color Theme to switch between different color themes.
Install Extensions:

Type >install and select Extensions: Install Extensions to browse and install extensions from the marketplace.
Run a Task:

Type >run task and select Tasks: Run Task to execute predefined tasks like building your project or running scripts.
Format Document:

Type >format and select Format Document to automatically format the current document according to the language's formatting rules.
Toggle Sidebar Visibility:

Type >toggle sidebar and select View: Toggle Side Bar Visibility to show or hide the sidebar.
Open Settings:

Type >settings and select Preferences: Open Settings to open the settings editor where you can configure various options.
Toggle Integrated Terminal:

Type >terminal and select Terminal: Toggle Integrated Terminal to show or hide the integrated terminal.
Git Commands:

Type >git and select from commands like Git: Clone, Git: Commit, or Git: Pull to perform version control operations.
Open Command Palette from Within the Palette:

While the Command Palette is open, you can type > to bring up the command list, allowing you to quickly switch tasks.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Extensions play a crucial role in Visual Studio Code (VS Code) by enhancing its functionality and customizing the development environment to suit specific needs and workflows. Extensions can add support for new programming languages, debuggers, linters, themes, and more.

Finding, Installing, and Managing Extensions
Finding Extensions
Marketplace:

Open the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or by pressing Ctrl+Shift+X.
Browse featured, popular, and recommended extensions in the Marketplace.
Use the search bar at the top of the Extensions view to find specific extensions.
Command Palette:

Open the Command Palette with Ctrl+Shift+P.
Type Extensions: Install Extensions and press Enter to open the Extensions view and search for extensions.
Installing Extensions
Via Extensions View:

In the Extensions view, find the extension you want to install.
Click the Install button next to the extension name.
Via Command Palette:

Open the Command Palette with Ctrl+Shift+P.
Type Extensions: Install Extensions and search for the extension.
Select the extension from the list and click Install.
Managing Extensions
Enable/Disable Extensions:

Open the Extensions view.
Click the gear icon next to the installed extension and select Enable or Disable.
Uninstall Extensions:

Open the Extensions view.
Click the gear icon next to the installed extension and select Uninstall.
Update Extensions:

VS Code will notify you when updates are available for your installed extensions. You can update them individually or all at once from the Extensions view.
Configure Extensions:

Some extensions have settings that can be configured. Click the gear icon next to the extension and select Extension Settings.
Examples of Essential Extensions for Web Development
HTML, CSS, and JavaScript

HTML Snippets: Provides snippets for HTML.
CSS IntelliSense: Enhances CSS support with IntelliSense for CSS class names.
JavaScript (ES6) code snippets: Offers a comprehensive set of JavaScript ES6 code snippets.
Frameworks and Libraries

React Native Tools: Provides support for React Native development, including IntelliSense and debugging.
Vue.js Extension Pack: Offers a set of extensions for Vue.js development, including syntax highlighting and IntelliSense.
Code Formatting and Linting

Prettier - Code formatter: Automatically formats your code according to defined style rules.
ESLint: Integrates ESLint into VS Code to provide JavaScript linting.
Version Control

GitLens: Enhances Git integration with features like blame annotations, code lens, and a Git explorer.
GitHub Pull Requests and Issues: Allows you to manage GitHub pull requests and issues directly from VS Code.
Debugging

Debugger for Chrome: Allows you to debug JavaScript code running in Google Chrome directly from VS Code.
Live Server: Launches a local development server with a live reload feature for static and dynamic pages.
Productivity Tools

Path Intellisense: Provides autocompletion for file paths.
Live Share: Enables real-time collaborative editing and debugging.
Theme and Appearance

Material Theme: A popular theme with various color schemes.
Material Icon Theme: A widely used icon theme that enhances the visual representation of files and folders.


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   The integrated terminal in Visual Studio Code (VS Code) provides a convenient way to access the command line directly within the editor. This feature enhances productivity by allowing developers to execute commands without leaving the development environment.

Opening the Integrated Terminal
Using the Menu:

Go to View > Terminal in the menu bar.
Keyboard Shortcut:

Press Ctrl+ (backtick) or Ctrl+Shift+ (backtick).
Command Palette:

Open the Command Palette with Ctrl+Shift+P.
Type Terminal: Create New Integrated Terminal and press Enter.
Using the Integrated Terminal
Basic Usage:

Once opened, the terminal appears at the bottom of the VS Code window.
You can execute any command just like in a standalone terminal, such as navigating directories, running scripts, or using version control commands.
Multiple Terminals:

You can create multiple terminal instances by clicking the + icon in the terminal panel or using the Command Palette with Terminal: Create New Integrated Terminal.
Switch between terminals using the dropdown menu in the terminal panel or by pressing Ctrl+ (backtick) repeatedly.
Terminal Tabs:

Each terminal instance is represented by a tab in the terminal panel, allowing you to manage multiple terminals easily.
Split Terminals:

You can split the terminal view by right-clicking a terminal tab and selecting Split Terminal, or using the split button next to the + button.
This allows you to view and interact with multiple terminals side by side.
Customization:

You can customize the shell used by the integrated terminal in File > Preferences > Settings. Search for terminal.integrated.shell.windows to set your preferred shell (e.g., Command Prompt, PowerShell, Git Bash).
Change the font size, cursor style, and other terminal settings by searching for terminal.integrated in the settings.
Advantages of Using the Integrated Terminal Compared to an External Terminal
Convenience:

The integrated terminal allows you to run commands directly within the editor, reducing the need to switch between the editor and an external terminal.
Context Awareness:

The terminal opens in the context of the workspace folder, making it easier to run commands related to your project without additional navigation.
Integrated Experience:

Having the terminal within VS Code provides a more seamless development experience. For example, you can run build commands, see the output, and immediately fix any issues in your code without switching windows.
Synchronization:

The terminal shares the same environment as VS Code, ensuring consistency in environment variables, paths, and other settings.
Multiple Terminals:

Easily manage multiple terminal sessions within a single interface, including splitting terminals and organizing tabs.
Extensions and Customization:

Extensions can interact with the integrated terminal, providing additional functionalities such as terminal snippets, tasks, and more.
Customize the terminal appearance and behavior to match your workflow.
Task Integration:

Integrate terminal commands with VS Code tasks, allowing you to automate repetitive actions like running tests or deploying code.
Code Navigation:

Easily navigate to files and lines referenced in terminal output by clicking on the paths and line numbers, which are hyperlinked to the corresponding locations in your code.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   Creating, opening, and managing files and folders in Visual Studio Code (VS Code) is straightforward and enhances productivity by offering a variety of methods to navigate and manipulate your project structure efficiently. Here’s a comprehensive guide on how to perform these tasks:

Creating Files and Folders
Using the Explorer View:

Open the Explorer view by clicking the Explorer icon in the Activity Bar or pressing Ctrl+Shift+E.
Create a New File:
Right-click on a folder or the blank space in the Explorer view.
Select New File.
Enter the name of the new file and press Enter.
Create a New Folder:
Right-click on a folder or the blank space in the Explorer view.
Select New Folder.
Enter the name of the new folder and press Enter.
Using the Command Palette:

Open the Command Palette with Ctrl+Shift+P.
Type File: New File or File: New Folder and press Enter.
Follow the prompts to create the file or folder.
Keyboard Shortcuts:

New File: Press Ctrl+N to create a new untitled file. Save it with Ctrl+S and specify the directory and filename.
New Folder: There isn’t a direct shortcut, but you can quickly create a folder using the Explorer view.
Opening Files and Folders
Using the Explorer View:

Double-click on a file to open it in the editor.
Single-click on a file to preview it without opening a new tab. To pin the preview (make it a permanent tab), double-click the tab.
Using the Command Palette:

Open the Command Palette with Ctrl+Shift+P.
Type File: Open File or File: Open Folder and press Enter.
Browse and select the file or folder you want to open.
Using the File Menu:

Go to File > Open File or File > Open Folder in the menu bar.
Browse and select the file or folder.
Keyboard Shortcuts:

Open File: Press Ctrl+O to open a file dialog.
Open Folder: Press Ctrl+K Ctrl+O to open a folder dialog.
Managing Files and Folders
Rename Files and Folders:

Right-click on the file or folder in the Explorer view.
Select Rename.
Enter the new name and press Enter.
Move Files and Folders:

Drag and drop the file or folder to the desired location in the Explorer view.
Alternatively, right-click the file or folder, select Cut, navigate to the destination folder, right-click, and select Paste.
Delete Files and Folders:

Right-click on the file or folder in the Explorer view.
Select Delete.
Confirm the deletion if prompted.
Navigating Between Files and Directories Efficiently
Quick Open:

Press Ctrl+P to open the Quick Open dialog.
Start typing the name of the file you want to open. VS Code will suggest matching files from your workspace.
Use the arrow keys to navigate through the suggestions and press Enter to open the selected file.
Go to Symbol:

Press Ctrl+Shift+O to open the Go to Symbol dialog.
Type the name of the symbol (e.g., function, variable) you want to navigate to. VS Code will suggest matching symbols in the current file.
Use the arrow keys to navigate through the suggestions and press Enter to jump to the symbol.
Go to Definition:

Right-click on a symbol in your code and select Go to Definition, or press F12 to navigate to the definition of the symbol.
Breadcrumb Navigation:

The breadcrumb navigation bar at the top of the editor shows the current file path and allows you to quickly navigate between files and directories.
Click on any part of the path to navigate to that directory or file.
Explorer View Navigation:

Use the arrow keys to navigate through the file tree in the Explorer view.
Press Enter to open a file or expand/collapse a folder.
File Tabs:

Use the tabs at the top of the editor to switch between open files.
Middle-click (or Ctrl+W) on a tab to close it.
Split Editor:

Right-click on a tab and select Split Right or Split Down to view multiple files side by side.
You can also drag a tab to the side or bottom of the editor to split the view.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   In Visual Studio Code (VS Code), users can find and customize settings through the Settings interface. Settings can be adjusted globally or at the workspace level, allowing for a high degree of customization. Here’s how to access and modify settings for changing the theme, font size, and keybindings:

Accessing Settings
Using the Menu:

Go to File > Preferences > Settings (or Code > Preferences > Settings on macOS).
Using the Command Palette:

Open the Command Palette with Ctrl+Shift+P.
Type Preferences: Open Settings and press Enter.
Keyboard Shortcut:

Press Ctrl+, to open the Settings directly.
Changing the Theme
Using the Command Palette:

Open the Command Palette with Ctrl+Shift+P.
Type Preferences: Color Theme and press Enter.
A list of available themes will appear. Use the arrow keys to navigate through the themes and press Enter to select the one you want.
Using the Settings UI:

Open the Settings UI.
In the search bar at the top, type theme.
Click on Color Theme to see and select from the available themes.
Changing the Font Size
Using the Settings UI:

Open the Settings UI.
In the search bar at the top, type font size.
Look for Editor: Font Size in the results.
Change the value to your desired font size (e.g., 14, 16).
Directly Editing settings.json:

Open the Command Palette with Ctrl+Shift+P.
Type Preferences: Open Settings (JSON) and press Enter.
Add or update the following entry:
"editor.fontSize": 16
Customizing Keybindings
Using the Menu:

Go to File > Preferences > Keyboard Shortcuts (or Code > Preferences > Keyboard Shortcuts on macOS).
Using the Command Palette:

Open the Command Palette with Ctrl+Shift+P.
Type Preferences: Open Keyboard Shortcuts and press Enter.
Keyboard Shortcut:

Press Ctrl+K Ctrl+S to open the Keyboard Shortcuts editor.
Modifying Keybindings
Find a Keybinding to Change:

In the Keyboard Shortcuts editor, search for the command you want to change the keybinding for (e.g., Save).
Change the Keybinding:

Click on the pencil icon next to the command you want to change.
Press the new key combination you want to use.
Press Enter to save the new keybinding.
Remove a Keybinding:

Click on the key combination next to the command.
Press Backspace to remove the keybinding.
Press Enter to confirm.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

Step-by-Step Guide to Debug a Simple Program
Install Necessary Extensions:

Ensure you have the appropriate language extension installed. For example, for Python, install the Python extension; for JavaScript/TypeScript, the built-in support should suffice.
Open or Create a Project:

Open VS Code.
Create a new file or open an existing project. For a new file, go to File > New File, write your code, and save it with the appropriate file extension.
Write a Simple Program:

Write a basic program in your chosen language (e.g., Python or JavaScript).
Configure the Debugger:

Open the Run and Debug view by clicking the play icon in the Activity Bar on the left or press Ctrl+Shift+D.
Click Create a launch.json file if prompted, or click the gear icon and select Add Configuration.
Choose the appropriate environment (e.g., Python or Node.js for JavaScript).
Modify launch.json:

The launch.json file will open in the editor. This file contains debug configurations.
Ensure the configuration matches your project's needs.
Set Breakpoints:

Open the file you want to debug.
Click in the gutter (left margin) next to the line number where you want to set a breakpoint. A red dot will appear, indicating the breakpoint.
Start Debugging:

In the Run and Debug view, select the appropriate configuration from the dropdown.
Click the green play button to start debugging, or press F5.
The debugger will start, and the program will pause execution at the breakpoints.
Key Debugging Features in VS Code
Breakpoints:

Set breakpoints to pause execution at specific lines of code.
Use conditional breakpoints and logpoints for advanced scenarios.
Variable Inspection:

Inspect variables and expressions in the VARIABLES pane.
Hover over variables in the editor to see their current value.
Watch Expressions:

Add expressions to the WATCH pane to monitor their values during execution.
Call Stack:

View the call stack to see the sequence of function calls that led to the current point of execution.
Step Controls:

Continue: Resume execution until the next breakpoint.
Step Over: Execute the next line of code without stepping into functions.
Step Into: Step into functions to debug line-by-line.
Step Out: Step out of the current function to the caller.
Integrated Terminal:

Use the integrated terminal for input/output operations during debugging.
Debug Console:

Execute commands and evaluate expressions in the Debug Console.
Example Summary
Install Extensions: Ensure language-specific extensions are installed.
Open/Create Project: Create or open a file with your code.
Write Code: Write a simple program.
Configure Debugger: Create and configure launch.json.
Set Breakpoints: Click in the gutter to set breakpoints.
Start Debugging: Select the configuration and start debugging with the play button or F5.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    Initializing a Repository
Open VS Code:

Open your project folder in VS Code.
Initialize Git Repository:

Open the Source Control view by clicking the Source Control icon in the Activity Bar on the left or by pressing Ctrl+Shift+G.
Click the Initialize Repository button in the Source Control view.
This action will create a new .git folder in your project directory, indicating that a new Git repository has been initialized.
Making Commits
Stage Changes:

Make changes to your files.
In the Source Control view, you will see a list of changed files under the "Changes" section.
Hover over a file and click the + (plus) icon to stage individual files or click the + icon at the top of the section to stage all changes.
Write a Commit Message:

In the text box at the top of the Source Control view, write a meaningful commit message describing the changes you made.
Commit Changes:

After writing your commit message, click the checkmark icon (Commit) above the message box.
This action will commit your staged changes to the local repository.
Pushing Changes to GitHub
Set Up Remote Repository:

If you haven't already, create a new repository on GitHub.
Copy the repository URL (usually ends with .git).
Add Remote Repository in VS Code:

Open the Command Palette by pressing Ctrl+Shift+P.
Type "Git: Add Remote" and select the command.
Enter a name for the remote (e.g., origin).
Paste the GitHub repository URL you copied earlier.
Push Changes:

After adding the remote repository, go to the Source Control view.
Click the ... (ellipsis) icon for more actions.
Select Push to push your commits to the GitHub repository.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

