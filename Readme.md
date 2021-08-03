# fvm vscode
> This project aimed at providing a isolated vscode enviroment for flutter with fvm.

### Prerequisite
You should config fvm in the project first to follow the steps below.

### How to use
1. Change the paths in`PATH`
    1. git
    2. bash (powershell)
    3. fvm location (replace D:\Library\flutter\.pub-cache\bin)
    4. other os related variable (ex. should include powershell If you are windows)
2. *(optional)* Add other env variables in `terminal.integrated.env.windows` or extend `PATH` as you wish.
3. [Toggle Integrated Terminal](https://code.visualstudio.com/docs/editor/integrated-terminal) and **reopen vscode**.
4. Now, the `flutter` cli in the terminal is `fvm` version, so you don't need to do `fvm flutter ...`.

