# Ghostty config teasks
## graphics issue on older hardware
https://github.com/ghostty-org/ghostty/discussions/8836

previous version
https://github.com/mkasberg/ghostty-ubuntu/releases/tag/1.1.3-0-ppa2


## issues over ssh
Fix:

```
infocmp -x xterm-ghostty | ssh YOUR-SERVER -- tic -x -
```

From:
https://ghostty.org/docs/help/terminfo#copy-ghostty's-terminfo-to-a-remote-machine
