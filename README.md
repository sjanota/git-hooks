# git-hooks

### How To
1. Clone it to `~/git-hooks`
1. To enable it add following lines to `.gitconfig`
```
[include]
  path = "~/git-hooks"
```
1. Apply one of styles to your repository, for example scala style
```
repo-dir$ git hooks scala
```

### Styles

* scala
  1. Adds branch name as [BRANCH_NAME] at the beginning of commit message if branch name matches pattern `^[A-Z]{3}-[0-9]+$`
  1. Runs tests, integration tests and scalamft checks before commit


* scala-no-it
  1. Adds branch name as [BRANCH_NAME] at the beginning of commit message if branch name matches pattern `^[A-Z]{3}-[0-9]+$`
  1. Runs tests and scalamft checks before commit
