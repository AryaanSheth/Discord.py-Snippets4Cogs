# Discord.py Snippets4Cogs README
A simple [Discord.py](https://github.com/Rapptz/discord.py) boilerplate generator updated for 2022

The extension is inspired by [discord.py Code Snippets by Wasi Master](https://marketplace.visualstudio.com/items?itemName=WasiMaster.discord-py-snippets).
The code in the snippets is a simple and effective way to load multiple cogs for a Discord.py project.

![demo](images/example.gif)

## v1.0.2 Release
- main.py cog management generator
- cog.py base template code
- setup.py (cog) ```on_ready``` code

## Create Local Extension
```git
cd ./.vscode/extensions
git clone https://github.com/AryaanSheth/Discord.py-Snippets4Cogs
```
> You will not receive live updates if you download the library locally
## Requirements
```bash
pip install discord.py
pip install discord
```
## Starting A Project
In your project root create a main.py file and type !cogmain
create a new folder in root called ```cogs``` 
In the folder create startup.py and type !startup
To create a custom cog, create a new file *cogName*.py and type !cog

## Commands
| Command  | Output                      |
|----------|-----------------------------|
| !cogmain | boilerplate for main.py     |
| !startup | boilerplate for startup cog |
| !cog     | boilerplate for general cog |

## Release Notes
### 1.0.0
Initial release of code
### 1.0.1
Added ```!cogs``` and ```!startup```
### 1.0.2
Fixed some some bugs when generating file

## Source
[Github](https://github.com/AryaanSheth/Discord.py-Snippets4Cogs)
