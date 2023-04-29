#!/bin/bash

# if not logged into Github, do login
if gh auth status 2>&1 >/dev/null | grep -q "not logged"; then
  gh auth login
fi
 
result=${PWD##*/}
echo "# Project $result" > README.md
git init -b main
git add README.md
git commit -m "initial commit"
gh repo create --source=. --public --push
