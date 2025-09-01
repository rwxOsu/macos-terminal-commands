# macos-terminal-commands
Fenster fliegen nicht in andere Spaces wenn man sie an den Rand zieht (10s Verzögerung)
```
defaults write com.apple.dock workspaces-edge-delay -float 10; killall Dock
```
