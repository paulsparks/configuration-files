# Configuration Files
## Setup
For the .bashrc\_prefs file to be loaded, add the following to your .bashrc:
```
# include .bashrc_prefs if it exists
if [ -f $HOME/.bashrc_prefs ]; then
  . $HOME/.bashrc_prefs
fi
```

