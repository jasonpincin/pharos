pharos
======

Coordinate processes in distributed applications.

## example

```
var pharosTree = require('pharos/tree')
```

See [pharos-tree](https://github.com/jasonpincin/pharos-tree) [api docs](https://github.com/jasonpincin/pharos-tree#api).

## todo

* peer - easily share tree state between processes
* server - allow access to tree state from non-peers

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
