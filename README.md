# gitconfig

## Installing

### OS

#### Arch

```
yay -S git
```

#### macOS

`git` pre-installed on macOS is not good enough:

```
brew install git gpg
```

## Clone config

```
git clone git@github.com:belminf/dotgit.git ~/.config/git
```

## Setup GPG signing

```
# Select "RSA and RSA" with 4096 bits
gpg --full-gen-key
```

# Local config

Keep in `~/.config/git/config.local`.
