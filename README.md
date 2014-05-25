pharos
======

Coordinate processes in distributed applications.

** UNSTABLE ** - Not recommended to be used in anything serious at the moment.

## example

```
var pharosTree = require('pharos/tree')
```

See [pharos-tree](https://github.com/jasonpincin/pharos-tree#api) API docs. 

## testing

`npm test [--dot | --spec] [--coverage]`

### options

* `--dot` - output test results as dots instead of tap
* `--spec` - output test results as spec instead of tap
* `--coverage` - display text cover report

### patterns

Only test files matching a certain pattern may be run by prefixing the 
test command with `grep=pattern`. Example:

```
grep=connect npm test --dot
```

### watching

First:
`npm install -g nodemon`

Then you can:
`nodemon -x npm test [--dot | --spec] [--coverage]`

### html coverage report

Open it with `npm run view-cover` or `npm run vc`
