# tag-testing

Repo to test github action for tagging

`commit` on master.

`git tag -a v0.0.1 -m "first version tag"`

`git log --oneline`

```shell
4d1436d (HEAD -> main, tag: v0.0.1, origin/main, origin/HEAD) First commit on master
e1bf9ca Initial commit
```

`git tag --list`

```shell
v0.0.1
```

Tag new commit with new version

```shell
git tag -a v1.0.0 -m "first major version on main"
git push origin --tags
```

`git log --oneline`

```shell
b150dc1 (HEAD -> main, tag: v1.0.0, origin/main, origin/HEAD) Add git log from v0.0.1 tag to readme.md
4d1436d (tag: v0.0.1) First commit on master
e1bf9ca Initial commit
```
