# Full Stack Web Development Setup
This is my own web development setup which I use to build Full Stack JS applications, I'm going to include everything including themes, fonts, etc.
This might always be **updated depending** on what tech stack I'll be using in the future.

**Operating System**: Linux PopOS
Download Link: https://system76.com/pop

## Git/GitHub
Git is a version control system and it's integrated with many websites like **GitHub**

`sudo apt install git-all`

Then generate your keys and add them to GitHub:

`ssh-keygen -t rsa -b 4096 -C "your_email@example.com"`

Follow the prompts, then run:

`eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa`

Then add the key to your GitHub account:
https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account

## Command Line
My main command line interface is **Hyper**
Download Hyper: https://hyper.is/

- Hyper Setup:
    - Theme: hyper-dracula
    - Font: fira code(size 12)
    - Other Plugins: hypercwd, hyperpower

I also use **zsh** bash instead of the original terminal because I can customize it the way I want :smile: 

Install **Oh My Zsh**: https://github.com/ohmyzsh/ohmyzsh/wiki

My zsh theme is called: **Spaceship ZSH**
https://denysdovhan.com/spaceship-prompt/

## IDE
My favorite is **VSCode** for sure!

Latest version from the site:
https://code.visualstudio.com/Download

**Important VScode Settings**:
1. To allow eslint to work in both server and client directories
`"eslint.workingDirectories": [
        "./client", "./server"
    ]`
    
2. To use zsh shell in VScode 
`    "terminal.integrated.shell.osx": "/usr/local/bin/zsh"`

**Current Theme**: Dracula

**Other themes**: 
 - Material
 - CodeSandBox
 - OneDarkPro

**Current Font**: Dank Mono, fira code(fall back)

**Extentions**:
-    Auto Rename Tag
-    Bracket Pair Colorizer
-    Code Spell Checker
-    Code Time
-    Color Highlight
-    Debugger For Chrome
-    ES7 React/Redux/GraphQL/React-Native snippets
-    ESlint
-    GitLens
-    Import Cost
-    IntelliSense 
-    JavaScript (ES6) snippets
-    Live Sass Compiler
-    Live Server
-    Live Share
-    Prettier
-    Quokka.js 
-    Sass
-    vscode-spotify

That's a lot of extentions :neutral_face: but it's all cool :100: 

## Browser 
It's gotta be **Google Chrome** https://www.google.com/chrome/

Important Chrome Extentions:
- LightHouse
- Accessibility Developer Tools
- JSONView
- Octotree
- React Dev Tools
- Redux Dev Tools

## Node JS
First we need to enable the node source repo
`curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
`
**Note**: You might have to use sudo before the command and you can change the version by changing `10.x` to the desired version

Then we will be abel to install node via the command 
`sudo apt install nodejs`

Then check the node version to make sure it's installed 
`node --version`

## Databases
**Postgres**
You can follow this repo to install **postgreSQL** database along with the **pgcli**
https://github.com/macintoshhelper/learn-sql/blob/master/postgresql/setup.md





