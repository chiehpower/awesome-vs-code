# Visual Studio Code 
[![](https://img.shields.io/badge/Author-Chieh-blue)](./) 

I think being a programmer who must know how to use the debug tool whatever who uses what kind of code editor or IDE.  If we know how to use the debug tool, it can enhance our coding efficiency. I think you guys already understood what I mean.  

## Debug mode tutorials

First, we can press **F5** to start debugging mode or you can also find it on here.

![](assets/f5.png)

After we start debugging mode, it will appear a small control board.

![](assets/control-board.png)

Of course, it seems to happen nothing and running as normal because we haven't flag lines what we wanna track.

Hence, before we start debugging mode, let's flag some lines that we can see the number near by our codes. We just click it and it will display the "red dot" (i.e., Breakpoints). It means that you wanna check this line during using debugging.

![](assets/red-dot.png)

Suppose we flag 5 dots and press F5 again, and then it is going to check the lines of what you flag.

### Introduction of buttons

Next, we are going to introduce those buttons meaning to teach you how to use them.

| Icon | Name | Description     |
| ---- | ---- | ---- |
|  ![](assets/cb1.png)    | Continue | When you start debugging mode, it will go to the first dot, and then you can press this button that it will jump to the second dot directly.   |
|  ![](assets/cb2.png)    | Step Over | This button will run line by line. For example, first dot is at line 47. When you press it, it will go to line 48.    |
|  ![](assets/cb3.png)    | Step Info | Step Info is a little bit different with Step Over. Step Info will go into the function (e.g., definition) if there is a function inside in that line. For example, you have A and B scripts, and A needs to call the definition from B. When you implement on that definition in A script, it will go into the definition of B script. Also, when it goes to a for loop, it will also bring you into that for loop.  |
|  ![](assets/cb4.png)    | Step Out | According to last example, when you go into B script, you can press this button to go back to the A script.  |
|  ![](assets/cb5.png)    | Restart | You don't need to leave the debugging mode and press F5 again. You can directly press this button to run again.     |
|  ![](assets/cb6.png)    | Stop | Stop / leave debugging mode.     |

### Introduction of debug console

Sequentially, debug console is also a quite important part. When we start debugging mode, how can we track the variables? Use it, debug console.

First step, open the terminal and choose the "DEBUG CONSOLE".

PS if you haven't started debugging mode, you cannot use it.
![](assets/console.png)

OK. Go ahead. 

Let's see my example.
Suppose I wanna check this variable of `a` to see its value. 
![](assets/a1.png)
When I typed `a`, I got the error because it hasn't passed this line. It hasn't implemented this line.

Hence, we run into next line and type again.
![](assets/a2.png)
See. We can get the value of variable `a`.

Of course, we can see more detail about this variable from "debug area" on the sidebar.

![](assets/sidebar.png)

Expand the `a` and then we can see there are more detail information of variable `a`. I deeply believe that sometimes these information is quite helpful.

---

## Recommend my favorite entensions of VS Code


Extension List:

- [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
- [Atom One Dark Theme](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)
- [Power Mode](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

Options:

- [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
- [Markdown Notes](https://marketplace.visualstudio.com/items?itemName=kortina.vscode-markdown-notes&ssr=false#overview)
- [Auto Comment Blocks](https://marketplace.visualstudio.com/items?itemName=kevinkyang.auto-comment-blocks)
- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)
- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
- [CMake Tools](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cmake-tools)
- [C++ Intellisense](https://marketplace.visualstudio.com/items?itemName=austin.code-gnu-global)
- [C/C++](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Coding Tracker](https://marketplace.visualstudio.com/items?itemName=hangxingliu.vscode-coding-tracker)
- [Compare Folders](https://marketplace.visualstudio.com/items?itemName=moshfeu.compare-folders)
- [Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)
- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
- [Path Autocomplete](https://marketplace.visualstudio.com/items?itemName=ionutvmi.path-autocomplete)
- [Python for VSCode](https://marketplace.visualstudio.com/items?itemName=tht13.python)
- [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)
- [TabNine](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)
- [vscode-pdf](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf)
- [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)
- [WakaTime](https://marketplace.visualstudio.com/items?itemName=WakaTime.vscode-wakatime)
- [VSCode Neovim](https://marketplace.visualstudio.com/items?itemName=asvetliakov.vscode-neovim)

---
# Introduction of Code runner

This is a handy extension of VS code. Sometimes you installed it but it cannot work normally because the tool name issue. For example, the default command name of implementing python is using **python** on command line. However, most of devices are installing both version of python, so there are python and python3 and we wanna use **python3** to run the code. Hence, here is my solution to resolve that problem. 

For code runner extension,

1. Turn on "code-runner.runInTerminal": true
2. Add this code in your setting.json file.
	```
    "code-runner.executorMap": {
        "python": "$pythonPath -u $fullFileName"
	```

---
# Introduction of GitLens

To be continued...

---

# Introduction of the plug-in of Remote-SSH

The icon and settings are a little bit different between Linux and Windows.

Here is the **Windows** part for setup remote-ssh plug-in.

1. Install the Remote-SSH plug-in in the **Extensions** area.

![](./Remote-SSH/ssh-6.png)

2. After we install the plugin of Remote - SSH, let’s click this icon to enter the Remote control area. ![](./Remote-SSH/ssh-1.png)

3. If you install many remote control plug-in such as WSL, container, or ssh, please choose the option of SSH TARGETS. In the WIN, VS Code integrates them in one area.
   ![](./Remote-SSH/ssh-2.png)
   
4. Press the buttom of “Add New” (plus symbol).

5. Fill in your remote IP and your port number.
   For example, `ssh -p (port) username@ip`
   ![](./Remote-SSH/ssh-3.png)
   
6. Click this “Connect to Host in the new Window” buttom
   ![](./Remote-SSH/ssh-4.png)
   
   It will create a new window for this remote use. Also, we can see the lower left (corner) that it will show the status of connection. 
   ![](./Remote-SSH/ssh-4-1.png)
   
7. Please type your password

8. We can see the statue that it already connected to remote server. The more information is displayed on **Output** area. You can switch to **Terminal** area. In addition, it will show the whole folders of remote side that you can easily use it. 

   ![](./Remote-SSH/ssh-5.png)

Done~