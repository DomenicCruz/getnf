# getNF
###
Works with older curl versions (ex. from ubuntu repo) + some fixes.
Props to original author: ronniedroid
###
## -Usage-
## A better way to install NerdFonts

### Dependencies

- curl 
- unzip
- fzf
- fontconfig

### Installation

```
git clone https://github.com/ronniedroid/getnf.git
cd getnf
./install.sh
```

### Usage

run `getnf` from the terminal and it will represent you with a list of NerdFonts with fzf, select the ones you want, and let it do it's work.

By default the downloaded archives are removed, But if you give `getnf` the `-k` flag, it will not remove the Archives from $HOME/Downloads/NerdFonts

Enjoy!
