# api documentation for  [levelup (v1.3.5)](https://github.com/level/levelup)  [![npm package](https://img.shields.io/npm/v/npmdoc-levelup.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-levelup) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-levelup.svg)](https://travis-ci.org/npmdoc/node-npmdoc-levelup)
#### Fast & simple storage - a Node.js-style LevelDB wrapper

[![NPM](https://nodei.co/npm/levelup.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/levelup)

[![apidoc](https://npmdoc.github.io/node-npmdoc-levelup/build/screenCapture.buildCi.browser.apidoc.html.png)](https://npmdoc.github.io/node-npmdoc-levelup/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-levelup/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-levelup/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "leveldown": false,
        "leveldown/package": false,
        "semver": false
    },
    "bugs": {
        "url": "https://github.com/level/levelup/issues"
    },
    "contributors": [
        {
            "name": "Rod Vagg",
            "url": "https://github.com/rvagg"
        },
        {
            "name": "John Chesley",
            "url": "https://github.com/chesles/"
        },
        {
            "name": "Jake Verbaten",
            "url": "https://github.com/raynos"
        },
        {
            "name": "Dominic Tarr",
            "url": "https://github.com/dominictarr"
        },
        {
            "name": "Max Ogden",
            "url": "https://github.com/maxogden"
        },
        {
            "name": "Lars-Magnus Skog",
            "url": "https://github.com/ralphtheninja"
        },
        {
            "name": "David Björklund",
            "url": "https://github.com/kesla"
        },
        {
            "name": "Julian Gruber",
            "url": "https://github.com/juliangruber"
        },
        {
            "name": "Paolo Fragomeni",
            "url": "https://github.com/0x00a"
        },
        {
            "name": "Anton Whalley",
            "url": "https://github.com/No9"
        },
        {
            "name": "Matteo Collina",
            "url": "https://github.com/mcollina"
        },
        {
            "name": "Pedro Teixeira",
            "url": "https://github.com/pgte"
        },
        {
            "name": "James Halliday",
            "url": "https://github.com/substack"
        },
        {
            "name": "Jarrett Cruger",
            "url": "https://github.com/jcrugzz"
        }
    ],
    "dependencies": {
        "deferred-leveldown": "~1.2.1",
        "level-codec": "~6.1.0",
        "level-errors": "~1.0.3",
        "level-iterator-stream": "~1.3.0",
        "prr": "~1.0.1",
        "semver": "~5.1.0",
        "xtend": "~4.0.0"
    },
    "description": "Fast & simple storage - a Node.js-style LevelDB wrapper",
    "devDependencies": {
        "async": "~1.5.0",
        "bustermove": "~1.0.0",
        "delayed": "~1.0.1",
        "faucet": "~0.0.1",
        "leveldown": "^1.1.0",
        "memdown": "~1.1.0",
        "msgpack-js": "~0.3.0",
        "referee": "~1.2.0",
        "rimraf": "~2.4.3",
        "slow-stream": "0.0.4",
        "tap": "~2.3.1",
        "tape": "~4.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "fa80a972b74011f2537c8b65678bd8b5188e4e66",
        "tarball": "https://registry.npmjs.org/levelup/-/levelup-1.3.5.tgz"
    },
    "gitHead": "ed5a54202085839784f1189f1266e9c379d64081",
    "homepage": "https://github.com/level/levelup",
    "keywords": [
        "leveldb",
        "stream",
        "database",
        "db",
        "store",
        "storage",
        "json"
    ],
    "license": "MIT",
    "main": "lib/levelup.js",
    "maintainers": [
        {
            "name": "rvagg"
        },
        {
            "name": "ralphtheninja"
        },
        {
            "name": "juliangruber"
        }
    ],
    "name": "levelup",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/level/levelup.git"
    },
    "scripts": {
        "test": "tape test/*-test.js | faucet"
    },
    "version": "1.3.5"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module levelup](#apidoc.module.levelup)
1.  [function <span class="apidocSignatureSpan"></span>levelup (location, options, callback)](#apidoc.element.levelup.levelup)
1.  [function <span class="apidocSignatureSpan">levelup.</span>destroy ()](#apidoc.element.levelup.destroy)
1.  [function <span class="apidocSignatureSpan">levelup.</span>repair ()](#apidoc.element.levelup.repair)
1.  [function <span class="apidocSignatureSpan">levelup.</span>super_ ()](#apidoc.element.levelup.super_)
1.  [function <span class="apidocSignatureSpan">levelup.</span>toString ()](#apidoc.element.levelup.toString)
1.  object <span class="apidocSignatureSpan">levelup.</span>errors

#### [module levelup.errors](#apidoc.module.levelup.errors)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>EncodingError (message, cause)](#apidoc.element.levelup.errors.EncodingError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>InitializationError (message, cause)](#apidoc.element.levelup.errors.InitializationError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>LevelUPError (message, cause)](#apidoc.element.levelup.errors.LevelUPError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>NotFoundError (message, cause)](#apidoc.element.levelup.errors.NotFoundError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>OpenError (message, cause)](#apidoc.element.levelup.errors.OpenError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>ReadError (message, cause)](#apidoc.element.levelup.errors.ReadError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>WriteError (message, cause)](#apidoc.element.levelup.errors.WriteError)



# <a name="apidoc.module.levelup"></a>[module levelup](#apidoc.module.levelup)

#### <a name="apidoc.element.levelup.levelup"></a>[function <span class="apidocSignatureSpan"></span>levelup (location, options, callback)](#apidoc.element.levelup.levelup)
- description and source-code
```javascript
function LevelUP(location, options, callback) {
  if (!(this instanceof LevelUP))
    return new LevelUP(location, options, callback)

  var error

  EventEmitter.call(this)
  this.setMaxListeners(Infinity)

  if (typeof location == 'function') {
    options = typeof options == 'object' ? options : {}
    options.db = location
    location = null
  } else if (typeof location == 'object' && typeof location.db == 'function') {
    options = location
    location = null
  }


  if (typeof options == 'function') {
    callback = options
    options  = {}
  }

  if ((!options || typeof options.db != 'function') && typeof location != 'string') {
    error = new InitializationError(
        'Must provide a location for the database')
    if (callback) {
      return process.nextTick(function () {
        callback(error)
      })
    }
    throw error
  }

  options      = getOptions(options)
  this.options = extend(defaultOptions, options)
  this._codec = new Codec(this.options)
  this._status = 'new'
  // set this.location as enumerable but not configurable or writable
  prr(this, 'location', location, 'e')

  this.open(callback)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.levelup.destroy"></a>[function <span class="apidocSignatureSpan">levelup.</span>destroy ()](#apidoc.element.levelup.destroy)
- description and source-code
```javascript
function deprecated() {
  warned = exports.printDeprecationMessage(msg, warned, deprecated);
  if (new.target) {
    return Reflect.construct(fn, arguments, new.target);
  }
  return fn.apply(this, arguments);
}
```
- example usage
```shell
...
  * <a href="#createKeyStream"><code>db.<b>createKeyStream()</b></code></a>
  * <a href="#createValueStream"><code>db.<b>createValueStream()</b></code></a>

### Special operations exposed by LevelDOWN

  * <a href="#approximateSize"><code>db.db.<b>approximateSize()</b></code></a>
  * <a href="#getProperty"><code>db.db.<b>getProperty()</b></code></a>
  * <a href="#destroy"><code><b>leveldown.destroy()</b></code></a>
  * <a href="#repair"><code><b>leveldown.repair()</b></code></a>

### Special Notes
  * <a href="#writeStreams">What happened to <code><b>db.createWriteStream()</b></code></a>


--------------------------------------------------------
...
```

#### <a name="apidoc.element.levelup.repair"></a>[function <span class="apidocSignatureSpan">levelup.</span>repair ()](#apidoc.element.levelup.repair)
- description and source-code
```javascript
function deprecated() {
  warned = exports.printDeprecationMessage(msg, warned, deprecated);
  if (new.target) {
    return Reflect.construct(fn, arguments, new.target);
  }
  return fn.apply(this, arguments);
}
```
- example usage
```shell
...
  * <a href="#createValueStream"><code>db.<b>createValueStream()</b></code></a>

### Special operations exposed by LevelDOWN

  * <a href="#approximateSize"><code>db.db.<b>approximateSize()</b></code></a>
  * <a href="#getProperty"><code>db.db.<b>getProperty()</b></code></a>
  * <a href="#destroy"><code><b>leveldown.destroy()</b></code></a>
  * <a href="#repair"><code><b>leveldown.repair()</b></code></a>

### Special Notes
  * <a href="#writeStreams">What happened to <code><b>db.createWriteStream()</b></code></a>


--------------------------------------------------------
<a name="ctor"></a>
...
```

#### <a name="apidoc.element.levelup.super_"></a>[function <span class="apidocSignatureSpan">levelup.</span>super_ ()](#apidoc.element.levelup.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.levelup.toString"></a>[function <span class="apidocSignatureSpan">levelup.</span>toString ()](#apidoc.element.levelup.toString)
- description and source-code
```javascript
toString = function () {
    return toString;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.levelup.errors"></a>[module levelup.errors](#apidoc.module.levelup.errors)

#### <a name="apidoc.element.levelup.errors.EncodingError"></a>[function <span class="apidocSignatureSpan">levelup.errors.</span>EncodingError (message, cause)](#apidoc.element.levelup.errors.EncodingError)
- description and source-code
```javascript
EncodingError = function (message, cause) {
  init.call(this, type, message, cause)
  //TODO: the specificity here is stupid, errno should be available everywhere
  if (type == 'FilesystemError') {
    this.code    = this.cause.code
    this.path    = this.cause.path
    this.errno   = this.cause.errno
    this.message =
      (errno.errno[this.cause.errno]
        ? errno.errno[this.cause.errno].description
        : this.cause.message)
      + (this.cause.path ? ' [' + this.cause.path + ']' : '')
  }
  Error.call(this)
  if (Error.captureStackTrace)
    Error.captureStackTrace(this, arguments.callee)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.levelup.errors.InitializationError"></a>[function <span class="apidocSignatureSpan">levelup.errors.</span>InitializationError (message, cause)](#apidoc.element.levelup.errors.InitializationError)
- description and source-code
```javascript
InitializationError = function (message, cause) {
  init.call(this, type, message, cause)
  //TODO: the specificity here is stupid, errno should be available everywhere
  if (type == 'FilesystemError') {
    this.code    = this.cause.code
    this.path    = this.cause.path
    this.errno   = this.cause.errno
    this.message =
      (errno.errno[this.cause.errno]
        ? errno.errno[this.cause.errno].description
        : this.cause.message)
      + (this.cause.path ? ' [' + this.cause.path + ']' : '')
  }
  Error.call(this)
  if (Error.captureStackTrace)
    Error.captureStackTrace(this, arguments.callee)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.levelup.errors.LevelUPError"></a>[function <span class="apidocSignatureSpan">levelup.errors.</span>LevelUPError (message, cause)](#apidoc.element.levelup.errors.LevelUPError)
- description and source-code
```javascript
LevelUPError = function (message, cause) {
  init.call(this, type, message, cause)
  //TODO: the specificity here is stupid, errno should be available everywhere
  if (type == 'FilesystemError') {
    this.code    = this.cause.code
    this.path    = this.cause.path
    this.errno   = this.cause.errno
    this.message =
      (errno.errno[this.cause.errno]
        ? errno.errno[this.cause.errno].description
        : this.cause.message)
      + (this.cause.path ? ' [' + this.cause.path + ']' : '')
  }
  Error.call(this)
  if (Error.captureStackTrace)
    Error.captureStackTrace(this, arguments.callee)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.levelup.errors.NotFoundError"></a>[function <span class="apidocSignatureSpan">levelup.errors.</span>NotFoundError (message, cause)](#apidoc.element.levelup.errors.NotFoundError)
- description and source-code
```javascript
NotFoundError = function (message, cause) {
  init.call(this, type, message, cause)
  //TODO: the specificity here is stupid, errno should be available everywhere
  if (type == 'FilesystemError') {
    this.code    = this.cause.code
    this.path    = this.cause.path
    this.errno   = this.cause.errno
    this.message =
      (errno.errno[this.cause.errno]
        ? errno.errno[this.cause.errno].description
        : this.cause.message)
      + (this.cause.path ? ' [' + this.cause.path + ']' : '')
  }
  Error.call(this)
  if (Error.captureStackTrace)
    Error.captureStackTrace(this, arguments.callee)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.levelup.errors.OpenError"></a>[function <span class="apidocSignatureSpan">levelup.errors.</span>OpenError (message, cause)](#apidoc.element.levelup.errors.OpenError)
- description and source-code
```javascript
OpenError = function (message, cause) {
  init.call(this, type, message, cause)
  //TODO: the specificity here is stupid, errno should be available everywhere
  if (type == 'FilesystemError') {
    this.code    = this.cause.code
    this.path    = this.cause.path
    this.errno   = this.cause.errno
    this.message =
      (errno.errno[this.cause.errno]
        ? errno.errno[this.cause.errno].description
        : this.cause.message)
      + (this.cause.path ? ' [' + this.cause.path + ']' : '')
  }
  Error.call(this)
  if (Error.captureStackTrace)
    Error.captureStackTrace(this, arguments.callee)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.levelup.errors.ReadError"></a>[function <span class="apidocSignatureSpan">levelup.errors.</span>ReadError (message, cause)](#apidoc.element.levelup.errors.ReadError)
- description and source-code
```javascript
ReadError = function (message, cause) {
  init.call(this, type, message, cause)
  //TODO: the specificity here is stupid, errno should be available everywhere
  if (type == 'FilesystemError') {
    this.code    = this.cause.code
    this.path    = this.cause.path
    this.errno   = this.cause.errno
    this.message =
      (errno.errno[this.cause.errno]
        ? errno.errno[this.cause.errno].description
        : this.cause.message)
      + (this.cause.path ? ' [' + this.cause.path + ']' : '')
  }
  Error.call(this)
  if (Error.captureStackTrace)
    Error.captureStackTrace(this, arguments.callee)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.levelup.errors.WriteError"></a>[function <span class="apidocSignatureSpan">levelup.errors.</span>WriteError (message, cause)](#apidoc.element.levelup.errors.WriteError)
- description and source-code
```javascript
WriteError = function (message, cause) {
  init.call(this, type, message, cause)
  //TODO: the specificity here is stupid, errno should be available everywhere
  if (type == 'FilesystemError') {
    this.code    = this.cause.code
    this.path    = this.cause.path
    this.errno   = this.cause.errno
    this.message =
      (errno.errno[this.cause.errno]
        ? errno.errno[this.cause.errno].description
        : this.cause.message)
      + (this.cause.path ? ' [' + this.cause.path + ']' : '')
  }
  Error.call(this)
  if (Error.captureStackTrace)
    Error.captureStackTrace(this, arguments.callee)
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
