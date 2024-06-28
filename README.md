[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292091&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
 STEPS TO DOWNLOAD AND INSTALL:
  1 Visit the visual studio code wesite and open the web browserand go to the visual studio code download page.
  2 Download the Installer:
  On the download page, you should see the "download for windows" button click it to start the VS code installer.
  3 Run the Installer:
  Once the download is completed navigate to the location where the was downloaded and double click the vscodesetup.exe to run the installer.
  4 Accept the License Agreement:
  In the installer window, you will be presented with the license agreement.Read through the terms and you agree, check the boxt accept and clock "Next"
  5 Select Istallation Location:
  Choose the destination the destination folder where you want to install Visual Studio Code. The default location is usually fine. Click "Next" to continue.
  6 Slect Additional Tasks:
  The installer will give you options for additional tasks, such as creating a desktop icon, adding VS Code to PATH, and more. It is recommended to check the options for adding to PATH, as  this makes it easier to launch VS Code from the command line. Click "Next" once you've made your selections.
  7 Install:
  Click the install" button to begin the installation process. This may take a few minutes.
  8 Launch Visual Studio Code:
  Once the installation is complete, you will see an option to launch Visual Studio Code. Check the box and click "Finish" to start VS Code immediatedly. Alternatively, you can find the Visual Studio Code icon on the desktop or in the start menu.
  9 Installation Extention:
  After launching Visual Studio Code, you may want to install extentions and enhance functionality. You can do this by clicking the on the extention icon in the sidebar or pressing Ctrl+Shift+X, then searching for and installing the desired extentions.
  Prerequisites:
  1 Windows 11 Operating System:Ensure your computer is running Windows 11.
  2 Internet Connection:Required to download the installation files.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
 Intial Configuration and Settings:
 1 Theme and Apperance:
 Install a theme that you find visually comfortable.Popular choices include Dracula Official, One Dark Pro and Master Theme.
 2 Editor Settings:
 They Include: Tab Size, Auto Save, Format on Save, Bracket Pair and Minimap.
 3 Version Control:
 - Set up Git by installing Git and configuring your username and email.
 - Enable the Source Control feature in VS Code to integrate Git.
 4 Extension:
 They Include:ESLint or TSLint, Prettier, Python, Pylance, IntelliCode, Live Server, Docker, Debugger, Jupyter, GitLens, Path Intellisense, and Settings Sync.
 5 Workspaces and Projects:
 Set up a workspace for differnt projects to keep settins and configurations isolated per project.
 6 Terminal:
 Customize the integratted terminal to use your prefered shell (eg bash, PowerShell)
 Setting These Configurations.
 1 Access Settings:
 Open setting by pressing (Crl + Cmd, on macOS)
 2 Add Extention:
 Open the Extenssion view by clicking on the Extesions icon in the Activity Bar on the side of the window or pressing Crl + Shift + X 
 3 Configure Extension:
 After installing, you may need to configure some extension by going to their settings.
3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
 1 Ativity Bar:
 Provides quick access to different views and fuctionalities. It contains icons of commonly used activities such as the Explorer, Search, Source Control, Run and Debug, and Extension. Each icon opens a corresponding view in the Side Bar.
 2 Side Bar:
 Displays different views and tool based on the selected activity from the Activity Bar. For example, when the Explorer Icon is selected, the Side Bar shows the file explorer. 
 3 Editor Group:
 Contains the open files and provides the editing space for your code or text. Multiple editor groups can be opened side-by-side  or stacked, allowing you to work on several files at once i a split-view setup. Each group can have multiple tabs for differnt files.
 4 Status Bar:
 Displays information about the current workspace and the active file. It shows details like the current branch, line and column numbers, language mode, encoding and more.
4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
 1 Installing Extensions:
 Type>exe and istal and search for the extensions to istall from the visual studio code marketplace.
 2 Running and Debugging Commands:
 Type>debug and slect various debug command such as Debugging or Add Configuration.
 3 Running Tasks:
 Type>task and select Tasks: Run Task to run predefied task.
 4 Git Command:
 Type>git and select commands like Git: Commit or Git: pull to perform Git operation.  
5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
 1 Finding Extensions:
 Open the extensions view by clicking the Extension icon in the activity bar on the side of the window. Use the serach bar at the top to find the extensions by name.
 2 Installing Extensions:
 Once you've found an extension you want to install, click the install button next to it's name.
 3 Managing Etension:
 To view istall extensions, go to the Extensions view and configure settings for individual extensions by clicking the gear icon and selecting Extension Setting.
 Essential Extension:
 1 ESLint.
 2 Live Server.
 3 Debugger for Chrome.
 4 GitLens.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
  - Opening Integrated Terminal:
   Open the command plalette with Ctrl + Shift + P
  - Using the Integrated Terminal:
 1 Creating New Terminal:
 Click the + button in the terminal panel.
 2 Managing Multiple Terminal:
 You can open multiple terminal sessions in tabs.
 3 Customizing the Terminal:
 Customize the terminal's apperance and behavior by going to File >Preference >Settings and searching for terminal.
 4 Running Commands:
 Run any command-line tools and scripts directly in the integrated terminal.
 ADVANTAGES:
 1 The integrated terminal allows you to stay within the VS Code enviroment, reducing the need to switch between the editor and external terminal.
 2 Workspace Integration:
 The terminal opens in the root directory of your workspace by default, making it easier to ren project-specific commands without navigation to the correct directory.
 3 Unified Interface:
 Having the terminal within the same window as your code allows for a more cohesive and oeganized workflow.
 4 The integrated terminal can be docked at the bottom.
7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. 
    1 Creating:
    - File: In Explorer, right-click >New File.
    - Folder: In Explorer, right-click >New Folder.
    2 Openning:
    - File: Double-click in Explorer.
    - Folder: Open folder button, File>Open Folder.
    3 Managing:
    Rename: Right-click>Rename.
    Delete: Right-click>Delete
    Move: Drag and drop.
  How can users navigate between different files and directories efficiently?
  1 Qick Open:
  Start typing the file name and select from the results.
  2 Explorer View:
  Click on files and directories in the Explorer view.
  3 Go to Defination:
  Right-click on a symbol and select Go to Definition.
8. Settings and Preferences:
   - Where can users find and customize settings in VS Code?
   In Visual Studio Code, users access and customize settings through the command palette (for JSON or UI settings), a gear icon in the sidebar, or the file menu under Preferences. They can manage global and workspace-specific configurations, search settings, and edit directly in the JSON file for precise customization.
    Provide examples of how to change the theme, font size, and keybindings.
    1 Changing Theme:
    Open VS Code, press Ctrl/Cmd + Shift + P to open the command palette.
    Type "Preferences: Color Theme" and select a theme from the list, such as "Dark+ (default dark)" or "Quiet Light (default light)".
    2 Font Size:
    - Similarly, open the command palette with Ctrl/Cmd + Shift + P.
    - Type "Preferences: Open Settings (JSON)" to open the settings in JSON format.
    - Add "editor.fontSize": 14 (or your preferred size) to set the font size to 14 pixels.
   3 Key binding:
     - Open the command palette (Ctrl/Cmd + Shift + P).
     - Type "Preferences: Open Keyboard Shortcuts (JSON)" to edit keybindings directly in JSON format.
     - Add custom keybindings like { "key": "ctrl+k", "command": "workbench.action.toggleSidebarVisibility" } to toggle the sidebar with Ctrl + K.
   9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
   1 Install Necessary Extensions:
    Ensure you have the appropriate debugging extensions installed for your programming language (e.g., for JavaScript/Node.js, you might need "Debugger for Chrome" or "Node.js Debug").
   2 Open Your Project:
     Open your project folder in VS Code. You can do this by selecting File > Open Folder... and choosing your project directory.
   3 Set a Breakpoint:
      Navigate to the file where you want to set a breakpoint (a point where program execution will pause for inspection).
      Click in the gutter area (to the left of the line numbers) to set a breakpoint. A red dot indicates the breakpoint.
   4 Configure Debugging Launch Configuration:
     Click on the Run and Debug icon in the Activity Bar on the side (or press Ctrl/Cmd + Shift + D).
     Click on the gear icon to create a launch configuration file (launch.json) and choose the environment (e.g., Node.js, Chrome).
   5 Start Debugging:
     Press the green play button (or F5) to start debugging. VS Code will launch your program in the configured environment and pause at the breakpoints.
   6 Debugging Features:
     Stepping through code: Use controls like Step Over (F10), Step Into (F11), and Step Out (Shift + F11) to navigate through your code line by line.
     Inspecting variables: Hover over variables to see their current values, or view them in the Variables panel.
     Watch expressions: Add expressions to monitor their values as you step through the code.
     Call stack: See the function call hierarchy and navigate through the stack frames.
     Debug console: Interact with your application by executing commands in the integrated debug console.
   7 Stop Debugging:
     Click the red square Stop button in the debug toolbar or press Shift + F5 to terminate the debug session.
10. Using Source Control:
    - How can users integrate Git with VS Code for version control?
    Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    1 Open VS Code:
    Launch VS Code and open the folder or workspace where you want to initialize the Git repository.
    2 Open the Terminal in VS Code:
      Open the integrated terminal in VS Code by selecting View > Terminal or using the shortcut Ctrl/Cmd + `.
    3 Initialize Git Repository:
      In the terminal, navigate to your project directory if not already there.
    4 Run the following command to initialize a Git repository:
    bash
    Copy code
    5 git inCommit Changes:
       Enter a commit message in the text box at the top of the Changes section.
       Press Ctrl/Cmd + Enter to commit your changes.
       Alternatively, you can commit changes using the terminal:
       bash
       Copy code
       git commit -m "Your commit message"it
    6 Add GitHub Repository as Remote:
      In the terminal (inside VS Code), add your GitHub repository as a remote:
      bash
      Copy code
      git remote add origin https://github.com/yourusername/your-repository.git
      Replace yourusername with your GitHub username and your-repository with the name of your repository.
    7 Push Changes to GitHub:
       Push your committed changes to GitHub:
      bash
      Copy code
      git push -u origin main
      Replace main with your branch name if it differs.
Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

