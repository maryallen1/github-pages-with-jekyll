# Welcome to my blog --- 
# Welcome to Ascensions GitHub Enterprise (GHE)

# I'm glad you are here.

We are thrilled to welcome you to Ascensions on-premise GitHub. For those familiar with git and GitHub already,
enjoy! For those new to git and/or GitHub, than here are some items that will help you on your journey.

# Useful links to get you started...
- On premise GitHub URL: https://github.ascension.org
- Git command cheatsheet: https://education.github.com/git-cheat-sheet-education.pdf
- Github lab: https://lab.github.com/ (requires a public github.com account)

**Getting Started**

**Choosing an Editor**
Select an editor that will suit your development needs. Although we do not support these editors, here are a few of the common IDE and development editors available:
- VS Code (free)
- Atom (free)
- GitHub Desktop (free)
- VIM (free)
- Visual Studio Professional $$

**Download and Install Git**

**Windows Device**
1. Visit https://git-scm.com/downloads and download the latest release of git.
2. Run the installer (i.e. Git-2.xx.x-64-bit.exe) from the download location you saved the exe.
3. A dialog box, Git 2.xx.x Setup, will appear. Click Next.
4. On the Select a Destination Location box, select a directory for Git to be installed. Click Next.
5. On the Select Components box, select the components to be installed with Git installation. Click Next.
6. On the Select the Start Menu folder screen, enter the name or choose a folder where the Git installation will place the program shortcuts. Click Next.
7. On the Choosing the Default Editor Used by Git screen, select an editor from the list (ideally the one you chose above) to be used by Git. Click Next.
- Recommended if using Visual Studio:
"Select other editor as Git's default editor"
Browse to: "C:\Program Files (x86)\Microsoft Visual Studio\2017\Community\Common7\IDE"
Select: 'devenv.exe'
- Recommended for VS Code:
Use Visual Studio Code as Git's default editor.
NOTE: You're welcome to use any editor of choice, but note that support for your IDE or editor is minimal to none.
8. On the Adjusting Your PATH Environment screen, keep the second option, Git from the Windows Command Prompt, to avoid disabling
Windows tools. Click Next.
9. On the Choosing the SSH executable, select the SSH client you would prefer Git to use. Click Next.
10. On the Choosing HTTPS Transport Backend screen, select the option Use the native Windows Secure Channel library. Click Next.NOTE:
This is STRONGLY RECOMMENDED to avoid SSL errors when using command-line.
11. On the Configuring the Line Ending Conversions screen, the default Windows style is recommended. Click Next.
12. On the Configuring the Terminal Emulator to Use with Git Bash screen, the MinTTy is recommended (easier and better scroll-back). Click Next.
13. On the Configuring Extra Options Screen, the defaults are recommended. Click Install.

**Mac Device**
- Should come preinstalled on Mac devices. To test, run git --version from Terminal.

**Getting Access**
- Based on KB article: ServiceNow KB Article
- Provide the following information in a ServiceNow request to AHNAT/ESD/PLAN AND AUTOM/DEVOPS:
  - First and Last Name
  - Department and Org level (e.g. ESD, Products, etc)
  - Email Address
  - Domain\Login
  - Application you are requesting access (e.g. github, jenkins, etc)

**First Time Logging In**
Although you have been added to the Active Directory group that allows you access to GHE, the next step is to login and create your portfolio. This initial step will generate a profile based on your Active Directory user and allow you the ability to start using GitHub and its rich set of features. When your profile gets created, please reach out to an administrator to be added to the Ascension Technologies organization, otherwise, you will be missing out on all the collaborative features Github offers.

**Create a Personal Access Token (PAT)**
- Creating a personal access token for the command line
Why is this needed: Since we are using SAML authentication, you will need to use this as your password when connecting via command-line. On Windows devices, this will get saved to your Windows Credential Manager. On Mac devices, this will be saved in your Key chain.
Alternatives: You can also save an SSH key to your account.

**Adding an SSH Key to your Account**
- Add SSH Key
Why is this needed: Useful for authenticating to GHE from command-line
Alternatives: You can also Create a Personal Access Token.

**Topics that will make transitioning easier**
- Git
- Git vs GitHub
- Branches and protected branches
- Pull Requests

**Other Git Related Documentation**
- GitHub Roles and Responsibilities
- Git and VisualStudio Setup Help
