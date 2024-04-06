# Installation

Add the following code snippet to your `/etc/pacman.conf`:

```
[vigarch]
SigLevel = Optional
Server = https://raw.github.com/cybercraftlabs/vigarch-pkg-repo/main/repo
```

Then, run `sudo pacman -Sy` to update repository.
