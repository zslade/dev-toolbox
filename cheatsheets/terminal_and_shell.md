# Terminal and shell cheatsheet

## File & directory management

```bash
touch new_file.py # create new file
mkdir folder_name
rm file_name # permanently deletes file unless tool installed or alias applied in zshrc
cat file_name # prints contents of file to screen
ls -a ~ | grep .zshrc # checks if .zshrc is in home directory by listing all files, including hidden, pipes (`|`) it to grep which filters out everything except lines that match `.zshrc`
```

## Terminal environment & configuration

```bash
source file_name # loads and executes file in current session
alias name="command" # creates a shortcut nickname for a long command
echo $VARIABLE # prints value of a system variable (e.g. $HOME or $PATH)
```

## App Launchers

```bash
code file_name.py # opens a file
code . # opens current folder inside vscode
open file_name.py # ppens a file using Mac's default graphical application
nano file_name.py # opens nano text editor inside terminal window
```