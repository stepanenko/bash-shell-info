
# Bash / Shell Notes

`SSH` - secure shell  
`~` - home directory  
`$` - logged in as a standard user (not as an admin)  

Bash scripts start with a shebang (`#!`) followed by a path to the application that should run it. E.g.: `#!/bin/zsh`

`pwd` - print current directory (absolute path)  
`echo` - prints the following message. E.g.: `echo "My first bash script"`  

`which $SHELL` - prints currently used shell

`ls -a` - list all files and folders (incl. hidden ones, beginning with dot)  
`ls -l` - long ditailed list  
`ls -la` - long ditailed incl. hidden

`cd` / `cd ~` - takes you home

`pushd <absolute_path>` - takes you to <absolute_path> but saves the current path  
`popd` - takes you back to the saved location

---
### Watching:
- [Beginner's Guide to the Bash Terminal [14:30]](https://www.youtube.com/watch?v=oxuRxtrO2Ag&ab_channel=JoeCollins)


## Shortcuts

Keys | Meaning
--- | ---
CMD + L | Clear last terminal's output
CMD + K | Clear all terminal's output
