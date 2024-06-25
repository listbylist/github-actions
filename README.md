# github-actions

Reusable GitHub actions.

> [!IMPORTANT]
> :point_up: Please fork this repo before using it in your projects.

## Actions

### npm-make-{prj,test}

Npm actions setup nodejs, npm, make environment. They expect package.json and package-lock.json files in the subproject directory.

#### npm-make-prj

Runs project by executing `make init` and `make (path)` inside subproject directory.
  
```yaml
uses: listbylist/github-actions/npm-make-prj@main
with:
  path: subproject-path
```
  
#### npm-make-test

Runs tests by executing `make init-test` and `make test` inside subproject directory

```yaml
uses: listbylist/github-actions/npm-make-test@main
with:
  path: subproject-path
```

## Licence

The MIT License
