# silimium

## Init a submodule

```
git submodule add -b master git@github.com:silimium/community.git editions/community
git submodule set-branch --branch . editions/community
git submodule update --remote --recursive
```

## Add a bundle as submodule

```shell
git submodule add -b master git@github.com:silimium/task-feature.git src/Silimium/TaskBundle
git submodule set-branch --branch . src/Silimium/TaskBundle
```
