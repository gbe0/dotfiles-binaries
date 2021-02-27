# Dot Files - Binaries

This repo should be checked out into `~/.local/mybin`. Binaries in this script are generally built from the `binbuilder` Dockerfile; this repo is for initial bootstrap purposes.

## Usage

Checkout the repo into `~/.local/mybin`. As the repository may be quite large due to the nature of the files, it may be checked out with the `depth` parameter set to `1`:

```bash
git clone --depth=1 git@github.com:gbe0/dotfiles-binaries.git ~/.local/mybin
```

After cloning the repo, the `.git` folder can be completely removed as future updates can be handled directly by the binbuilder script:

```bash
rm -rf ~/.local/mybin/.git
```

Alternatively the repo zip file can be [downloaded from GitHub](https://github.com/gbe0/dotfiles-binaries) and extracted to the folder.

