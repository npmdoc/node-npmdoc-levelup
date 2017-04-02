# api documentation for  [levelup (v1.3.5)](https://github.com/level/levelup)  [![npm package](https://img.shields.io/npm/v/npmdoc-levelup.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-levelup) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-levelup.svg)](https://travis-ci.org/npmdoc/node-npmdoc-levelup)
#### Fast & simple storage - a Node.js-style LevelDB wrapper

[![NPM](https://nodei.co/npm/levelup.png?downloads=true)](https://www.npmjs.com/package/levelup)

[![apidoc](https://npmdoc.github.io/node-npmdoc-levelup/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-levelup_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-levelup/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-levelup/build/screen-capture.npmPackageListing.svg)



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
            "email": "r@va.gg",
            "url": "https://github.com/rvagg"
        },
        {
            "name": "John Chesley",
            "email": "john@chesl.es",
            "url": "https://github.com/chesles/"
        },
        {
            "name": "Jake Verbaten",
            "email": "raynos2@gmail.com",
            "url": "https://github.com/raynos"
        },
        {
            "name": "Dominic Tarr",
            "email": "dominic.tarr@gmail.com",
            "url": "https://github.com/dominictarr"
        },
        {
            "name": "Max Ogden",
            "email": "max@maxogden.com",
            "url": "https://github.com/maxogden"
        },
        {
            "name": "Lars-Magnus Skog",
            "email": "ralphtheninja@riseup.net",
            "url": "https://github.com/ralphtheninja"
        },
        {
            "name": "David Björklund",
            "email": "david.bjorklund@gmail.com",
            "url": "https://github.com/kesla"
        },
        {
            "name": "Julian Gruber",
            "email": "julian@juliangruber.com",
            "url": "https://github.com/juliangruber"
        },
        {
            "name": "Paolo Fragomeni",
            "email": "paolo@async.ly",
            "url": "https://github.com/0x00a"
        },
        {
            "name": "Anton Whalley",
            "email": "anton.whalley@nearform.com",
            "url": "https://github.com/No9"
        },
        {
            "name": "Matteo Collina",
            "email": "matteo.collina@gmail.com",
            "url": "https://github.com/mcollina"
        },
        {
            "name": "Pedro Teixeira",
            "email": "pedro.teixeira@gmail.com",
            "url": "https://github.com/pgte"
        },
        {
            "name": "James Halliday",
            "email": "mail@substack.net",
            "url": "https://github.com/substack"
        },
        {
            "name": "Jarrett Cruger",
            "email": "jcrugzz@gmail.com",
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
            "name": "rvagg",
            "email": "rod@vagg.org"
        },
        {
            "name": "ralphtheninja",
            "email": "ralphtheninja@riseup.net"
        },
        {
            "name": "juliangruber",
            "email": "julian@juliangruber.com"
        }
    ],
    "name": "levelup",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
1.  [function <span class="apidocSignatureSpan">levelup.</span>batch (levelup, codec)](#apidoc.element.levelup.batch)
1.  [function <span class="apidocSignatureSpan">levelup.</span>destroy ()](#apidoc.element.levelup.destroy)
1.  [function <span class="apidocSignatureSpan">levelup.</span>repair ()](#apidoc.element.levelup.repair)
1.  [function <span class="apidocSignatureSpan">levelup.</span>super_ ()](#apidoc.element.levelup.super_)
1.  object <span class="apidocSignatureSpan">levelup.</span>batch.prototype
1.  object <span class="apidocSignatureSpan">levelup.</span>errors
1.  object <span class="apidocSignatureSpan">levelup.</span>util

#### [module levelup.batch](#apidoc.module.levelup.batch)
1.  [function <span class="apidocSignatureSpan">levelup.</span>batch (levelup, codec)](#apidoc.element.levelup.batch.batch)

#### [module levelup.batch.prototype](#apidoc.module.levelup.batch.prototype)
1.  [function <span class="apidocSignatureSpan">levelup.batch.prototype.</span>clear ()](#apidoc.element.levelup.batch.prototype.clear)
1.  [function <span class="apidocSignatureSpan">levelup.batch.prototype.</span>del (key_, options)](#apidoc.element.levelup.batch.prototype.del)
1.  [function <span class="apidocSignatureSpan">levelup.batch.prototype.</span>put (key_, value_, options)](#apidoc.element.levelup.batch.prototype.put)
1.  [function <span class="apidocSignatureSpan">levelup.batch.prototype.</span>write (callback)](#apidoc.element.levelup.batch.prototype.write)

#### [module levelup.errors](#apidoc.module.levelup.errors)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>EncodingError (message, cause)](#apidoc.element.levelup.errors.EncodingError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>InitializationError (message, cause)](#apidoc.element.levelup.errors.InitializationError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>LevelUPError (message, cause)](#apidoc.element.levelup.errors.LevelUPError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>NotFoundError (message, cause)](#apidoc.element.levelup.errors.NotFoundError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>OpenError (message, cause)](#apidoc.element.levelup.errors.OpenError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>ReadError (message, cause)](#apidoc.element.levelup.errors.ReadError)
1.  [function <span class="apidocSignatureSpan">levelup.errors.</span>WriteError (message, cause)](#apidoc.element.levelup.errors.WriteError)

#### [module levelup.util](#apidoc.module.levelup.util)
1.  [function <span class="apidocSignatureSpan">levelup.util.</span>dispatchError (db, error, callback)](#apidoc.element.levelup.util.dispatchError)
1.  [function <span class="apidocSignatureSpan">levelup.util.</span>getLevelDOWN ()](#apidoc.element.levelup.util.getLevelDOWN)
1.  [function <span class="apidocSignatureSpan">levelup.util.</span>getOptions (options)](#apidoc.element.levelup.util.getOptions)
1.  [function <span class="apidocSignatureSpan">levelup.util.</span>isDefined (v)](#apidoc.element.levelup.util.isDefined)
1.  object <span class="apidocSignatureSpan">levelup.util.</span>defaultOptions



# <a name="apidoc.module.levelup"></a>[module levelup](#apidoc.module.levelup)

#### <a name="apidoc.element.levelup.batch"></a>[function <span class="apidocSignatureSpan">levelup.</span>batch (levelup, codec)](#apidoc.element.levelup.batch)
- description and source-code
```javascript
function Batch(levelup, codec) {
  this._levelup = levelup
  this._codec = codec
  this.batch = levelup.db.batch()
  this.ops = []
  this.length = 0
}
```
- example usage
```shell
...

Encoding of the 'key' object will adhere to the ''keyEncoding'' option provided to <a href="#ctor"><code>levelup()</code></a>, although
 you can provide alternative encoding settings in the options for 'del()' (it's recommended that you stay consistent in your encoding
 of keys and values in a single store).

A ''sync'' option can also be passed, see <a href="#put"><code>put()</code></a> for details on how this works.

--------------------------------------------------------
<a name="batch"></a>
### db.batch(array[, options][, callback]) *(array form)*
<code>batch()</code> can be used for very fast bulk-write operations (both *put* and *delete*). The 'array' argument should contain
 a list of operations to be executed sequentially, although as a whole they are performed as an atomic operation inside LevelDB.

Each operation is contained in an object having the following properties: 'type', 'key', 'value', where the *type* is either ''put
'' or ''del''. In the case of ''del'' the ''value'' property is ignored. Any entries with a ''key'' of 'null' or 'undefined' will
 cause an error to be returned on the 'callback' and any ''type': 'put'' entry with a ''value'' of 'null' or 'undefined' will return
 an error.

If 'key' and 'value' are defined but 'type' is not, it will default to ''put''.

'''js
...
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



# <a name="apidoc.module.levelup.batch"></a>[module levelup.batch](#apidoc.module.levelup.batch)

#### <a name="apidoc.element.levelup.batch.batch"></a>[function <span class="apidocSignatureSpan">levelup.</span>batch (levelup, codec)](#apidoc.element.levelup.batch.batch)
- description and source-code
```javascript
function Batch(levelup, codec) {
  this._levelup = levelup
  this._codec = codec
  this.batch = levelup.db.batch()
  this.ops = []
  this.length = 0
}
```
- example usage
```shell
...

Encoding of the 'key' object will adhere to the ''keyEncoding'' option provided to <a href="#ctor"><code>levelup()</code></a>, although
 you can provide alternative encoding settings in the options for 'del()' (it's recommended that you stay consistent in your encoding
 of keys and values in a single store).

A ''sync'' option can also be passed, see <a href="#put"><code>put()</code></a> for details on how this works.

--------------------------------------------------------
<a name="batch"></a>
### db.batch(array[, options][, callback]) *(array form)*
<code>batch()</code> can be used for very fast bulk-write operations (both *put* and *delete*). The 'array' argument should contain
 a list of operations to be executed sequentially, although as a whole they are performed as an atomic operation inside LevelDB.

Each operation is contained in an object having the following properties: 'type', 'key', 'value', where the *type* is either ''put
'' or ''del''. In the case of ''del'' the ''value'' property is ignored. Any entries with a ''key'' of 'null' or 'undefined' will
 cause an error to be returned on the 'callback' and any ''type': 'put'' entry with a ''value'' of 'null' or 'undefined' will return
 an error.

If 'key' and 'value' are defined but 'type' is not, it will default to ''put''.

'''js
...
```



# <a name="apidoc.module.levelup.batch.prototype"></a>[module levelup.batch.prototype](#apidoc.module.levelup.batch.prototype)

#### <a name="apidoc.element.levelup.batch.prototype.clear"></a>[function <span class="apidocSignatureSpan">levelup.batch.prototype.</span>clear ()](#apidoc.element.levelup.batch.prototype.clear)
- description and source-code
```javascript
clear = function () {
  try {
    this.batch.clear()
  } catch (err) {
    throw new WriteError(err)
  }

  this.ops = []
  this.length = 0
  return this
}
```
- example usage
```shell
...

Queue a *del* operation on the current batch, not committed until a 'write()' is called on the batch.

The optional 'options' argument can be used to override the default ''keyEncoding''.

This method may 'throw' a 'WriteError' if there is a problem with your delete.

<b><code>batch.clear()</code></b>

Clear all queued operations on the current batch, any previous operations will be discarded.

<b><code>batch.length</code></b>

The number of queued operations on the current batch.
...
```

#### <a name="apidoc.element.levelup.batch.prototype.del"></a>[function <span class="apidocSignatureSpan">levelup.batch.prototype.</span>del (key_, options)](#apidoc.element.levelup.batch.prototype.del)
- description and source-code
```javascript
del = function (key_, options) {
  options = getOptions(options)

  var key = this._codec.encodeKey(key_, options)

  try {
    this.batch.del(key)
  } catch (err) {
    throw new WriteError(err)
  }
  this.ops.push({ type : 'del', key : key })
  this.length++

  return this
}
```
- example usage
```shell
...

Encoding of the 'key' and 'value' objects is the same as in <a href="#put"><code>put</code></a>.

LevelDB will by default fill the in-memory LRU Cache with data from a call to get. Disabling this is done by setting 'fillCache'
to 'false'.

--------------------------------------------------------
<a name="del"></a>
### db.del(key[, options][, callback])
<code>del()</code> is the primary method for removing data from the store.
'''js
db.del('foo', function (err) {
  if (err)
    // handle I/O or other error
});
'''
...
```

#### <a name="apidoc.element.levelup.batch.prototype.put"></a>[function <span class="apidocSignatureSpan">levelup.batch.prototype.</span>put (key_, value_, options)](#apidoc.element.levelup.batch.prototype.put)
- description and source-code
```javascript
put = function (key_, value_, options) {
  options = getOptions(options)

  var key   = this._codec.encodeKey(key_, options)
    , value = this._codec.encodeValue(value_, options)

  try {
    this.batch.put(key, value)
  } catch (e) {
    throw new WriteError(e)
  }
  this.ops.push({ type : 'put', key : key, value : value })
  this.length++

  return this
}
```
- example usage
```shell
...
var levelup = require('levelup')

// 1) Create our database, supply location and options.
//    This will create or open the underlying LevelDB store.
var db = levelup('./mydb')

// 2) put a key & value
db.put('name', 'LevelUP', function (err) {
  if (err) return console.log('Ooops!', err) // some kind of I/O error

  // 3) fetch by key
  db.get('name', function (err, value) {
if (err) return console.log('Ooops!', err) // likely the key was not found

// ta da!
...
```

#### <a name="apidoc.element.levelup.batch.prototype.write"></a>[function <span class="apidocSignatureSpan">levelup.batch.prototype.</span>write (callback)](#apidoc.element.levelup.batch.prototype.write)
- description and source-code
```javascript
write = function (callback) {
  var levelup = this._levelup
    , ops     = this.ops

  try {
    this.batch.write(function (err) {
      if (err)
        return dispatchError(levelup, new WriteError(err), callback)
      levelup.emit('batch', ops)
      if (callback)
        callback()
    })
  } catch (err) {
    throw new WriteError(err)
  }
}
```
- example usage
```shell
...
'''js
db.batch()
  .del('father')
  .put('name', 'Yuri Irsenovich Kim')
  .put('dob', '16 February 1941')
  .put('spouse', 'Kim Young-sook')
  .put('occupation', 'Clown')
  .write(function () { console.log('Done!') })
'''

<b><code>batch.put(key, value[, options])</code></b>

Queue a *put* operation on the current batch, not committed until a 'write()' is called on the batch.

The optional 'options' argument can be used to override the default ''keyEncoding'' and/or ''valueEncoding''.
...
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



# <a name="apidoc.module.levelup.util"></a>[module levelup.util](#apidoc.module.levelup.util)

#### <a name="apidoc.element.levelup.util.dispatchError"></a>[function <span class="apidocSignatureSpan">levelup.util.</span>dispatchError (db, error, callback)](#apidoc.element.levelup.util.dispatchError)
- description and source-code
```javascript
function dispatchError(db, error, callback) {
  typeof callback == 'function' ? callback(error) : db.emit('error', error)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.levelup.util.getLevelDOWN"></a>[function <span class="apidocSignatureSpan">levelup.util.</span>getLevelDOWN ()](#apidoc.element.levelup.util.getLevelDOWN)
- description and source-code
```javascript
function getLevelDOWN() {
  if (leveldown)
    return leveldown

  var requiredVersion  = require('../package.json').devDependencies.leveldown
    , leveldownVersion

  try {
    leveldownVersion = require('leveldown/package.json').version
  } catch (e) {
    throw requireError(e)
  }

  if (!require('semver').satisfies(leveldownVersion, requiredVersion)) {
    throw new LevelUPError(
        'Installed version of LevelDOWN ('
      + leveldownVersion
      + ') does not match required version ('
      + requiredVersion
      + ')'
    )
  }

  try {
    return leveldown = require('leveldown')
  } catch (e) {
    throw requireError(e)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.levelup.util.getOptions"></a>[function <span class="apidocSignatureSpan">levelup.util.</span>getOptions (options)](#apidoc.element.levelup.util.getOptions)
- description and source-code
```javascript
function getOptions(options) {
  if (typeof options == 'string')
    options = { valueEncoding: options }
  if (typeof options != 'object')
    options = {}
  return options
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.levelup.util.isDefined"></a>[function <span class="apidocSignatureSpan">levelup.util.</span>isDefined (v)](#apidoc.element.levelup.util.isDefined)
- description and source-code
```javascript
function isDefined(v) {
  return typeof v !== 'undefined'
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
