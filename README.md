# git_commands
Useful git commands

Add a tag

```
git tag TAG
```

Push the tag to the origin repository

```
git push origin TAG
```

Show refs, tags

```
git show-ref
```

Show remote tags

```
git ls-remote --tags
```

Delete a tag locally

```
git -d TAG
```

Delete a remote tag

```
git push --delete origin TAG
```

# Go
Publishing a Go module with a version

```
git tag $VERSION
git commit -am "Changes for my module $VERSION"
git tag $VERSION
git push orign $VERSION
git push
```

List the
go list -m github.com/myrepo/mymodule@${$VERSION}
