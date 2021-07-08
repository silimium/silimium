# silimium

## Init a submodule

```
git submodule add -b master git@github.com:silimium/community.git editions/community
git submodule set-branch --branch . editions/community
git submodule update --remote --recursive
```

## Add a component as submodule

```shell
git submodule add -b master git@github.com:silimium/task-component.git components/task-component
git submodule set-branch --branch . components/task-component
```
