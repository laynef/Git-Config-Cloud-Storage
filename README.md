# Git Config

## Installation
```
Clone in '~' directory
cp ./.prepush-example ./.git/hooks/pre-push
git remote remove origin
git remote add origin <YOUR-GITHUB-LINK>
git add .
git commit -m 'Initial commit'
git push --set-upstream origin master
```

## Updates
Make your updates in this repo to '.gitconfig' then commit and push the changes to your github 