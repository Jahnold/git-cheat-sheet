Collection of useful git commands

# Tags

List all tags:
```
git tag
```

Create a new tag:
```
git tag [tag name]
```

Push new tag to remote:
```
git push origin [tag name]
```

# Fetch/Pull

Fetch one branch whilst having another branch checked out:
```
git fetch [remote] [sourceBranch]:[destinationBranch]
```
ie:
```
git fetch origin master:master
```
