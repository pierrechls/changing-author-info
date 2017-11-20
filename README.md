[![version](https://img.shields.io/badge/version-1.0.0-green.svg?style=flat-square)](https://github.com/pierrechls/changing-author-info)

# changing-author-info

> Changing the Git history of your repository using a script with parameters

## :rocket: How to use it

#### Getting script from the repository

```bash
$ wget https://raw.githubusercontent.com/pierrechls/changing-author-info/master/git-author-rewrite.sh
```

#### Run the script

```bash
$ ./git-author-rewrite.sh "old-email@example.com" "Correct Name" "correct-email@example.com"
```

#### Review the new Git history for errors

#### Push the corrected history to GitHub:

```bash
git push --force --tags origin 'refs/heads/*'
```

## :tada: Credits

Project inspired by a [github article](https://help.github.com/articles/changing-author-info/).
