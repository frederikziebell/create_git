# Create skeleton of a Github repo from local directory

## Rationale
You have a local directory with some files that you want to turn into a git repo and prepare for pushing it to Github. The command `create_git` simply initializes a git repo in the current directory, create a Github repo of the name of the current directory and commits an initial README.md file.

## Installation
1. Install [Github CLI]([url](https://github.com/cli))
2. Run
```
git clone https://github.com/frederikziebell/create_github
mkdir -p $HOME/bin
cp create_github/create_github $HOME/bin/create_github
chmod +x $HOME/bin/create_github
```
3. Ensure that `$HOME/bin` is part of `$PATH`, e.g. by adding 
```
export PATH="$HOME/bin:$PATH"
```
to `~/.bashrc` or `~/.zshrc`.

## Usage
1. navigate to a local directory
    `cd local_dir`
2. run
    `create_github`
