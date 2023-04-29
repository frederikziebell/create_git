# Create skeleton of a Github repo from local directory

## Rationale
You have a local directory with some files that you want to turn into a git repo and prepare for pushing it to Github. The command `create_git` simply initializes a git repo in the current directory, create a Github repo of the name of the current directory and commits an initial README.md file.

## Installation
```
git clone https://github.com/frederikziebell/create_github
cp create_github/create_github ~/.local/bin/create_github
chmod +x ~/.local/bin/create_github
```

## Usage
1. navigate to local directory
    `cd local_dir`
2. run
    `create_github`
