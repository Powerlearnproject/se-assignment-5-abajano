[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15282277&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

-Visit the VS Code website, download the Windows installer.

Run the installer, accept the agreement, select installation options, and complete the setup.
Prerequisite is a compatible Windows 11 system.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

-Configure settings like font size, tab size, and theme via File > Preferences > Settings.
Install essential extensions like Python, ,GitLens, Live Server, Prettier etc from the Extensions view using command (Ctrl+Shift+X).

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

-Activity Bar: Access different views.
Side Bar: Content related to selected view.
Editor Group: Edit files.
Status Bar: Information about project/files.


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

Access with Ctrl+Shift+P. Perform tasks like opening files, or running commands, switching between themes etc

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

-These are tools to enhance functionality. 
Isers can Find/install/manage in Extensions view. Some essential extensions: Python, GitLens, Live Server, Prettier etc

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

-Open with Ctrl+`. 
Advantages: direct access within editor, workspace integration. Advantages include direct access to the terminal within the editor and integration with the workspace.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

-Use Explorer view to manage files/folders. Navigate with Ctrl+P for quick file search. 


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

-Found in File > Preferences > Settings. Change theme using Command Palette, adjust font size/keybindings in settings.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

-Set up with launch.json file, start with F5 or Debug view. 
Features: breakpoints, call stack inspection.


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

-To integrate Git with VS Code for version control;

Begin by configuring Git Username and email  in VS Code settings as follows;

●  Open the Integrated Terminal in VS Code by pressing Ctrl+` or from the View menu.

●  Set your Git username by typing:
git config --global user.name "Your Name"

●  Set your Git email by typing:
git config --global user.email "your_email@example.com"

The above commands will set one's username and email globally for all Git repositories.  L

●  Once done, verify the configuration with the following commands;

git config --global user.name
git config --global user.email


- After Verification, 

●  Open your project in VS Code.

●  Initialize a repository: Open the Command Palette (Ctrl+Shift+P), type Git: Initialize Repository, and select your project folder.

●  Make changes to your files.

●  Stage changes: In the Source Control view, stage your changes by clicking the ‘+’ icon next to the changed files.

●  Commit changes: Enter a commit message and press Ctrl+Enter

●  Push to GitHub: Set up a remote repository on GitHub, then push your commits by clicking the ’…‘ icon in the Source Control view and selecting  ’Push‘.




 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

