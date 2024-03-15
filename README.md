# github-actions

Reusable GitHub actions.

> NB! Please fork this repo before using it in your projects.

## Actions

### npm-make-{prj,test}

These actions setup nodejs, npm, make environment.

`npm-make-prj` - runs project by executing `make init` and `make (path)` inside subproject directory
  
```yaml
uses: ListByList/github-action/npm-make-prj@main
with:
  path: subproject-path
```
  
`npm-make-test` - runs tests by executing `make init-test` and `make test` inside subproject directory

```yaml
uses: ListByList/github-action/npm-make-test@main
with:
  path: subproject-path
```
