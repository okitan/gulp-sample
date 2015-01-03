# Gulp sample app

## install gulp

```bash
npm init
npm install --save-dev gulp coffee-script
```

## gulpfile

### init

```bash
$ cat gulpfile.coffee
gulp = require 'gulp'

gulp.task 'default', ->
```

### first gulp

```bash
$ gulp
[10:53:36] Requiring external module coffee-script/register
[10:53:36] Using gulpfile ~/codes/gulp-sample/gulpfile.coffee
[10:53:36] Starting 'default'...
[10:53:36] Finished 'default' after 76 μs
```

