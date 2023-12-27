# git_commands
Useful git commands

New branch

```
git branch newbranch
```

Push the branch to the git server

```
git push -u origin HEAD
```

Delete a local branch

```
git branch -D branch_name
```

Delete a remote branch

```
git push -d origin branch_name
```

Add a tag

```
git tag TAG
```

Push the tag to the origin repository

```
git push origin TAG
```

Delete a tag locally

```
git -d TAG
```

Delete a remote tag

```
git push --delete origin TAG
```

Show refs, tags

```
git show-ref
```

Show remote tags

```
git ls-remote --tags
```

# Go
Publishing a Go module with a version
https://go.dev/doc/modules/publishing

```
git tag $VERSION
git commit -am "Changes for my module $VERSION"
git tag $VERSION
git push orign $VERSION
git push
```

List the version or the latest

```
go list -m github.com/myrepo/mymodule@${$VERSION}
go list -m github.com/myrepo/mymodule@latest
```

Get the module or the latest in order to import it

```
go get github.com/myrepo/mymodule@${$VERSION}
go get github.com/myrepo/mymodule@latest
```

