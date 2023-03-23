# ByzantineGPT

## Pitch

ByzantineGPT is what would happen if OpenAI's gpt model developed dissociative-identity disorder. It is a shell script that enables users to use bespoke 'modes' that I have prompt-engineered *(sophisticated way of saying 'I wrote')*.

## Requirements

This script leverages a python tool called `sgpt` in order to tap into OpenAI's gpt model.

You can install it by typing the following command on your unix-based or unix operating system. 

also `dialog` is required for tui to werk


### Installing `dialog` on Linux

#### Ubuntu/Debian

```
sudo apt-get update
sudo apt-get install dialog
```

#### Fedora

```
sudo dnf install dialog
```

#### CentOS/RHEL

```
sudo yum install epel-release
sudo yum install dialog
```

### Arch Linux

```
sudo pacman -S dialog
```
### Void Linux
```

sudo xbps-install dialog

```

### Installing `dialog` on macOS using `brew`

```
brew install dialog
```

### Installing `dialog` using `nix`

```
nix-env -i dialog
```

### Installing `shell-gpt` using pip3 

```
pip3 install shell-gpt

```
*The dialog package is not a requirement per se. Since most unix and unix-based distros come with `whiptail`, instead of installing `dialog`, all occurrences of dialog can be replaced by the command `whiptail`.*

## Initialisation

1. Following this, you'll need to get an API-key from OpenAI.
2. Then, run the command:
```
sgpt 'Your-open-ai-key'

```
3. If this does not work, export your key to the following variable

```
export OPENAI_API_KEY="Your-api-key"
```

**Keep in mind that exporting your api-key is highly dangerous. In case you have added it to your shell's config file, please consider removing it before uploading your dotfiles, lest it compromise your privacy and security.**

***

Have fun you sick freaks. 
