# api documentation for  [atlasboard (v1.1.3)](http://atlasboard.bitbucket.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-atlasboard.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-atlasboard) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-atlasboard.svg)](https://travis-ci.org/npmdoc/node-npmdoc-atlasboard)
#### AtlasBoard is dashboard/wallboard framework written all in JS

[![NPM](https://nodei.co/npm/atlasboard.png?downloads=true)](https://www.npmjs.com/package/atlasboard)

[![apidoc](https://npmdoc.github.io/node-npmdoc-atlasboard/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-atlasboard_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-atlasboard/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-atlasboard/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-atlasboard/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Atlassian"
    },
    "bin": {
        "atlasboard": "./lib/cli/cli.js"
    },
    "contributors": [
        {
            "name": "William Archinal",
            "email": "william.archinal@gmail.com"
        },
        {
            "name": "Christoph Kiehl",
            "email": "ckiehl@atlassian.com"
        },
        {
            "name": "Alexander Dickson",
            "email": "alex@alexanderdickson.com"
        },
        {
            "name": "Ivan Loire",
            "email": "iloire@atlassian.com"
        },
        {
            "name": "Sam Day",
            "email": "sday@atlassian.com"
        }
    ],
    "dependencies": {
        "async": "^1.4.2",
        "body-parser": "^1.13.3",
        "cheerio": "^0.19.0",
        "colors": "^1.1.2",
        "compression": "^1.5.2",
        "connect-assets": "5.0.1",
        "css": "^2.2.1",
        "debug": "^2.2.0",
        "ejs": "2.3.3",
        "errorhandler": "^1.4.2",
        "express": "^4.12.3",
        "hardhat": "~0.0.7",
        "method-override": "2.3.5",
        "mkdirp": "~0.5.1",
        "moment": "^2.10.6",
        "morgan": "^1.6.1",
        "nib": "^1.1.0",
        "nock": "^2.10.0",
        "optimist": "~0.3.5",
        "pg": "4.3",
        "read-package-json": "^2.0.0",
        "request": "^2.61.0",
        "semver": "~2.0.11",
        "socket.io": "^1.3.6",
        "stylus": "0.52.0",
        "temp": "0.8.3",
        "tracer": "^0.8.0",
        "traverse": "^0.6.6",
        "underscore": "1.8.3",
        "xtend": "2.0.3"
    },
    "description": "AtlasBoard is dashboard/wallboard framework written all in JS",
    "devDependencies": {
        "bower": "^1.5.2",
        "bower-files": "^3.7.0",
        "expect.js": "0.1.2",
        "gulp": "^3.8.11",
        "gulp-concat": "^2.5.2",
        "gulp-eslint": "^1.0.0",
        "gulp-filter": "^2.0.2",
        "gulp-load-plugins": "^0.9.0",
        "gulp-mocha": "^2.1.3",
        "gulp-uglify": "^1.1.0",
        "gulp-watch": "^4.3.5",
        "mocha": "2.3.0",
        "proxyquire": "0.4.1",
        "rimraf": "2.1.4",
        "sinon": "1.16.1"
    },
    "directories": {},
    "dist": {
        "shasum": "b13f5e43e62ef2eef2e8364d2808c703dfd85f95",
        "tarball": "https://registry.npmjs.org/atlasboard/-/atlasboard-1.1.3.tgz"
    },
    "engines": {
        "node": ">=0.12",
        "npm": "~2.0.0"
    },
    "gitHead": "edf788f90ad3930e52c9de7a82b74da2fa923793",
    "homepage": "http://atlasboard.bitbucket.org",
    "keywords": [
        "server",
        "dashboard"
    ],
    "license": "Apache-2.0",
    "main": "./lib/atlasboard.js",
    "maintainers": [
        {
            "name": "ckiehl",
            "email": "ckiehl@atlassian.com"
        },
        {
            "name": "iloire",
            "email": "ivan@iloire.com"
        },
        {
            "name": "archinal",
            "email": "william.archinal@gmail.com"
        }
    ],
    "name": "atlasboard",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@bitbucket.org/atlassian/atlasboard.git"
    },
    "scripts": {
        "test": "mocha -b test --reporter list --ignore-leaks"
    },
    "version": "1.1.3",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "npm": "~2.0.0",
                "node": ">=0.12"
            },
            "pkgid": "atlasboard@1.1.3"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "npm": "~2.0.0",
                "node": ">=0.12"
            },
            "pkgid": "atlasboard@1.1.3"
        }
    ]
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module atlasboard](#apidoc.module.atlasboard)
1.  [function <span class="apidocSignatureSpan">atlasboard.</span>event_queue (io)](#apidoc.element.atlasboard.event_queue)
1.  [function <span class="apidocSignatureSpan">atlasboard.</span>scheduler (jobWorker)](#apidoc.element.atlasboard.scheduler)
1.  object <span class="apidocSignatureSpan">atlasboard.</span>event_queue.prototype
1.  object <span class="apidocSignatureSpan">atlasboard.</span>helpers
1.  object <span class="apidocSignatureSpan">atlasboard.</span>hipchat
1.  object <span class="apidocSignatureSpan">atlasboard.</span>item_manager
1.  object <span class="apidocSignatureSpan">atlasboard.</span>job_initialiser
1.  object <span class="apidocSignatureSpan">atlasboard.</span>job_manager
1.  object <span class="apidocSignatureSpan">atlasboard.</span>package_dependency_manager
1.  object <span class="apidocSignatureSpan">atlasboard.</span>path_resolver
1.  object <span class="apidocSignatureSpan">atlasboard.</span>scheduler.prototype
1.  object <span class="apidocSignatureSpan">atlasboard.</span>stylus
1.  object <span class="apidocSignatureSpan">atlasboard.</span>template_manager

#### [module atlasboard.event_queue](#apidoc.module.atlasboard.event_queue)
1.  [function <span class="apidocSignatureSpan">atlasboard.</span>event_queue (io)](#apidoc.element.atlasboard.event_queue.event_queue)

#### [module atlasboard.event_queue.prototype](#apidoc.module.atlasboard.event_queue.prototype)
1.  [function <span class="apidocSignatureSpan">atlasboard.event_queue.prototype.</span>send (id, data)](#apidoc.element.atlasboard.event_queue.prototype.send)

#### [module atlasboard.helpers](#apidoc.module.atlasboard.helpers)
1.  [function <span class="apidocSignatureSpan">atlasboard.helpers.</span>areValidPathElements (paths)](#apidoc.element.atlasboard.helpers.areValidPathElements)
1.  [function <span class="apidocSignatureSpan">atlasboard.helpers.</span>getJSONFromFile (path, defaultValue, warnIfFileNotExists, warnIfFileIsInvalid)](#apidoc.element.atlasboard.helpers.getJSONFromFile)
1.  [function <span class="apidocSignatureSpan">atlasboard.helpers.</span>getRndInt (min, max)](#apidoc.element.atlasboard.helpers.getRndInt)
1.  [function <span class="apidocSignatureSpan">atlasboard.helpers.</span>isPathContainedInRoot (pathDir, root)](#apidoc.element.atlasboard.helpers.isPathContainedInRoot)
1.  [function <span class="apidocSignatureSpan">atlasboard.helpers.</span>readJSONFile (dashboardPath, cb)](#apidoc.element.atlasboard.helpers.readJSONFile)

#### [module atlasboard.hipchat](#apidoc.module.atlasboard.hipchat)
1.  [function <span class="apidocSignatureSpan">atlasboard.hipchat.</span>create (options)](#apidoc.element.atlasboard.hipchat.create)

#### [module atlasboard.item_manager](#apidoc.module.atlasboard.item_manager)
1.  [function <span class="apidocSignatureSpan">atlasboard.item_manager.</span>get (packagesPath, itemType, extension, callback)](#apidoc.element.atlasboard.item_manager.get)
1.  [function <span class="apidocSignatureSpan">atlasboard.item_manager.</span>getByPackage (packagesPath, itemType, extension, callback)](#apidoc.element.atlasboard.item_manager.getByPackage)
1.  [function <span class="apidocSignatureSpan">atlasboard.item_manager.</span>getFirst (packagesPath, itemName, itemType, extension, callback)](#apidoc.element.atlasboard.item_manager.getFirst)
1.  [function <span class="apidocSignatureSpan">atlasboard.item_manager.</span>resolveCandidates (items, name, itemType, extension)](#apidoc.element.atlasboard.item_manager.resolveCandidates)
1.  [function <span class="apidocSignatureSpan">atlasboard.item_manager.</span>resolveLocation (name, itemType, extension)](#apidoc.element.atlasboard.item_manager.resolveLocation)

#### [module atlasboard.job_initialiser](#apidoc.module.atlasboard.job_initialiser)
1.  [function <span class="apidocSignatureSpan">atlasboard.job_initialiser.</span>init (options, cb)](#apidoc.element.atlasboard.job_initialiser.init)

#### [module atlasboard.job_manager](#apidoc.module.atlasboard.job_manager)
1.  [function <span class="apidocSignatureSpan">atlasboard.job_manager.</span>getJobs (options, callback)](#apidoc.element.atlasboard.job_manager.getJobs)

#### [module atlasboard.package_dependency_manager](#apidoc.module.atlasboard.package_dependency_manager)
1.  [function <span class="apidocSignatureSpan">atlasboard.package_dependency_manager.</span>installDependencies (packagesPath, callback)](#apidoc.element.atlasboard.package_dependency_manager.installDependencies)

#### [module atlasboard.path_resolver](#apidoc.module.atlasboard.path_resolver)
1.  [function <span class="apidocSignatureSpan">atlasboard.path_resolver.</span>fromAtlasboard ()](#apidoc.element.atlasboard.path_resolver.fromAtlasboard)
1.  [function <span class="apidocSignatureSpan">atlasboard.path_resolver.</span>fromLocalWallboard ()](#apidoc.element.atlasboard.path_resolver.fromLocalWallboard)

#### [module atlasboard.scheduler](#apidoc.module.atlasboard.scheduler)
1.  [function <span class="apidocSignatureSpan">atlasboard.</span>scheduler (jobWorker)](#apidoc.element.atlasboard.scheduler.scheduler)

#### [module atlasboard.scheduler.prototype](#apidoc.module.atlasboard.scheduler.prototype)
1.  [function <span class="apidocSignatureSpan">atlasboard.scheduler.prototype.</span>scheduleNext ()](#apidoc.element.atlasboard.scheduler.prototype.scheduleNext)
1.  [function <span class="apidocSignatureSpan">atlasboard.scheduler.prototype.</span>start ()](#apidoc.element.atlasboard.scheduler.prototype.start)

#### [module atlasboard.stylus](#apidoc.module.atlasboard.stylus)
1.  [function <span class="apidocSignatureSpan">atlasboard.stylus.</span>getMiddleware (options)](#apidoc.element.atlasboard.stylus.getMiddleware)
1.  [function <span class="apidocSignatureSpan">atlasboard.stylus.</span>getWidgetCSS (str, cb)](#apidoc.element.atlasboard.stylus.getWidgetCSS)

#### [module atlasboard.template_manager](#apidoc.module.atlasboard.template_manager)
1.  [function <span class="apidocSignatureSpan">atlasboard.template_manager.</span>resolveTemplateLocation (fileName, cb)](#apidoc.element.atlasboard.template_manager.resolveTemplateLocation)



# <a name="apidoc.module.atlasboard"></a>[module atlasboard](#apidoc.module.atlasboard)

#### <a name="apidoc.element.atlasboard.event_queue"></a>[function <span class="apidocSignatureSpan">atlasboard.</span>event_queue (io)](#apidoc.element.atlasboard.event_queue)
- description and source-code
```javascript
function EventQueue(io) {
  this.io = io;
  this.latestEvents = {};
  var self = this;

  io.on("connection", function (socket) {
    socket.on("resend", function (data) {
      if (self.latestEvents[data]) {
        socket.emit(data, self.latestEvents[data]);
      }
    });

    // broadcast logs
    socket.on("log", function (data) {
      socket.broadcast.emit('client', data);
    });
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.atlasboard.scheduler"></a>[function <span class="apidocSignatureSpan">atlasboard.</span>scheduler (jobWorker)](#apidoc.element.atlasboard.scheduler)
- description and source-code
```javascript
function Scheduler(jobWorker) {
  this.jobWorker = ensureSafeJobWorkerConfiguration(jobWorker);
  this.originalInterval = jobWorker.config.interval;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.atlasboard.event_queue"></a>[module atlasboard.event_queue](#apidoc.module.atlasboard.event_queue)

#### <a name="apidoc.element.atlasboard.event_queue.event_queue"></a>[function <span class="apidocSignatureSpan">atlasboard.</span>event_queue (io)](#apidoc.element.atlasboard.event_queue.event_queue)
- description and source-code
```javascript
function EventQueue(io) {
  this.io = io;
  this.latestEvents = {};
  var self = this;

  io.on("connection", function (socket) {
    socket.on("resend", function (data) {
      if (self.latestEvents[data]) {
        socket.emit(data, self.latestEvents[data]);
      }
    });

    // broadcast logs
    socket.on("log", function (data) {
      socket.broadcast.emit('client', data);
    });
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.atlasboard.event_queue.prototype"></a>[module atlasboard.event_queue.prototype](#apidoc.module.atlasboard.event_queue.prototype)

#### <a name="apidoc.element.atlasboard.event_queue.prototype.send"></a>[function <span class="apidocSignatureSpan">atlasboard.event_queue.prototype.</span>send (id, data)](#apidoc.element.atlasboard.event_queue.prototype.send)
- description and source-code
```javascript
send = function (id, data) {
  this.latestEvents[id] = data;
  this.io.emit(id, data); // emit to widget
  this.io.emit('client', {widgetId: id, data: data}); // emit to logger
}
```
- example usage
```shell
...

// unique id for this widget in the wallboard
jobWorker.id = jobWorker.dashboard_name + '-' +
    (jobWorker.widget_item.r || jobWorker.widget_item.row) + '-' +
    (jobWorker.widget_item.c || jobWorker.widget_item.col);

jobWorker.pushUpdate = function (data) {
  eventQueue.send(jobWorker.id, data);
};

// add security info
jobWorker.config.globalAuth = globalAuth;

if (jobWorker.widget_item.enabled !== false) {
...
```



# <a name="apidoc.module.atlasboard.helpers"></a>[module atlasboard.helpers](#apidoc.module.atlasboard.helpers)

#### <a name="apidoc.element.atlasboard.helpers.areValidPathElements"></a>[function <span class="apidocSignatureSpan">atlasboard.helpers.</span>areValidPathElements (paths)](#apidoc.element.atlasboard.helpers.areValidPathElements)
- description and source-code
```javascript
areValidPathElements = function (paths) {

  function valid(path){
    if (!path) {
      return false;
    }

    var malicius = false;
    path = path.toString(); //in case it is another type, like number

    if ((path.indexOf("/") !== -1) || (path.indexOf("\\") !== -1)) {
      malicius = true;
    }

    if (path.indexOf("..") !== -1) {
      malicius = true;
    }

    if (path.indexOf('\0') !== -1) {
      malicius = true;
    }

    if (malicius){
      console.log("Malicious path detected: %s", path);
      return false;
    }
    else {
      return true;
    }
  }

  paths = Array.isArray(paths) ? paths : [paths];
  return paths.every(valid);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.atlasboard.helpers.getJSONFromFile"></a>[function <span class="apidocSignatureSpan">atlasboard.helpers.</span>getJSONFromFile (path, defaultValue, warnIfFileNotExists, warnIfFileIsInvalid)](#apidoc.element.atlasboard.helpers.getJSONFromFile)
- description and source-code
```javascript
getJSONFromFile = function (path, defaultValue, warnIfFileNotExists, warnIfFileIsInvalid){
  try {
    if (!fs.existsSync(path)){
      if (warnIfFileNotExists) {
        warnIfFileNotExists(path);
      }
      return defaultValue;
    }
    return JSON.parse(fs.readFileSync(path));
  }
  catch (e){
    if (warnIfFileIsInvalid) {
      warnIfFileIsInvalid(path, e);
    }
    return defaultValue;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.atlasboard.helpers.getRndInt"></a>[function <span class="apidocSignatureSpan">atlasboard.helpers.</span>getRndInt (min, max)](#apidoc.element.atlasboard.helpers.getRndInt)
- description and source-code
```javascript
getRndInt = function (min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.atlasboard.helpers.isPathContainedInRoot"></a>[function <span class="apidocSignatureSpan">atlasboard.helpers.</span>isPathContainedInRoot (pathDir, root)](#apidoc.element.atlasboard.helpers.isPathContainedInRoot)
- description and source-code
```javascript
isPathContainedInRoot = function (pathDir, root){
  if (typeof root !== 'string' || typeof pathDir !== 'string'){
    return false;
  }

  if (pathDir[0] !== "/") {
    pathDir = path.join(process.cwd(), pathDir);
  }
  return pathDir.indexOf(root) === 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.atlasboard.helpers.readJSONFile"></a>[function <span class="apidocSignatureSpan">atlasboard.helpers.</span>readJSONFile (dashboardPath, cb)](#apidoc.element.atlasboard.helpers.readJSONFile)
- description and source-code
```javascript
readJSONFile = function (dashboardPath, cb) {
  fs.readFile(dashboardPath, function read(err, data){
    if (err) { return cb (err); }
    try {
      cb(null, JSON.parse(data));
    } catch(e){
      cb(e);
    }
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.atlasboard.hipchat"></a>[module atlasboard.hipchat](#apidoc.module.atlasboard.hipchat)

#### <a name="apidoc.element.atlasboard.hipchat.create"></a>[function <span class="apidocSignatureSpan">atlasboard.hipchat.</span>create (options)](#apidoc.element.atlasboard.hipchat.create)
- description and source-code
```javascript
create = function (options) {
  var request = options.request || require ('request');

  if (!options.api_key){
    throw 'api_key required';
  }

  var errors = {
    400: 'Bad request. Please check your data',
    401: 'Unauthorized: API KEY not valid',
    403: 'You have exceeded the rate limit',
    404: 'Not found',
    406: 'You requested an invalid content type',
    500: 'Server Error',
    503: 'The method you requested is currently unavailable (due to maintenance or high load'
  };

  var onResponseBuilder = function (callback) {
    return function (err, response, body) {
      if (callback) {
        var errMsg = null;
        if (err || !response || response.statusCode != 200) {
          errMsg = err;
          if (response && errors[response.statusCode]) {
            errMsg += ' ' + errors[response.statusCode] + '; ' + body;
          }
        }
        callback(errMsg, response ? response.statusCode : null, body);
      }
    };
  };

  return {
<span class="apidocCodeCommentSpan">    /**
     * Push message to HipChat server
     * @param roomId id of the room (number)
     * @param from sender name
     * @param message body of the message
     * @param notify should trigger a room notification? values: 1,0
     * @param callback a callback to be executed when complete
     */
</span>    'message' : function (roomId, from, message, notify, callback){
      var url = API_URL + 'v1/rooms/message?format=json&auth_token=' + options.api_key;

      var data = {
        'room_id' : roomId,
        'from' : from,
        'message' : message,
        'notify' : notify
      };

      request.post({
          url: url,
          headers:{'content-type': 'application/x-www-form-urlencoded'},
          body: qstring.stringify(data)
        }, onResponseBuilder(callback));
    },
    /**
     * Get a room info from hipchat
     * @param roomId id of the room (number)
     * @param callback a callback to be executed when complete
     */
    'roomInfo' : function (roomId, callback){
      var url = API_URL + 'v2/room/' + roomId + '?format=json&auth_token=' + options.api_key;
      request.get({url: url, json:true}, onResponseBuilder(callback));
    }
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.atlasboard.item_manager"></a>[module atlasboard.item_manager](#apidoc.module.atlasboard.item_manager)

#### <a name="apidoc.element.atlasboard.item_manager.get"></a>[function <span class="apidocSignatureSpan">atlasboard.item_manager.</span>get (packagesPath, itemType, extension, callback)](#apidoc.element.atlasboard.item_manager.get)
- description and source-code
```javascript
get = function (packagesPath, itemType, extension, callback) {
  this.getByPackage(packagesPath, itemType, extension, function (err, results) {
    if (err) {
      return callback(err);
    }
    var items = [];
    results.forEach(function (package) {
      items = items.concat(package.items);
    });
    callback(null, items);
  });
}
```
- example usage
```shell
...
 */

module.exports = {

onInit: function (config, dependencies) {
  dependencies.logger.info('adding routes...');
  dependencies.app.route("/jobs/mycustomroute")
      .get(function (req, res) {
        res.end('So something useful here');
      });

},

onRun: function (config, dependencies, jobCallback) {
  // code to be executed every interval
...
```

#### <a name="apidoc.element.atlasboard.item_manager.getByPackage"></a>[function <span class="apidocSignatureSpan">atlasboard.item_manager.</span>getByPackage (packagesPath, itemType, extension, callback)](#apidoc.element.atlasboard.item_manager.getByPackage)
- description and source-code
```javascript
getByPackage = function (packagesPath, itemType, extension, callback) {

  if (!Array.isArray(packagesPath)) {
    packagesPath = [packagesPath];
  }

  function readItemsFromPackageDir(dir, cb) {
    var package = {dir: dir};

    var itemDir = path.join(dir, itemType);
    if (!fs.existsSync(itemDir)) {
      package.items = [];
      return cb(null, package);
    }

    // this functions parses:
    // - packages/default/<itemType>/*
    // - packages/otherpackages/<itemType>/*
    // for dashboards, or:
    // - packages/default/<itemType>/*/*.js
    // - packages/otherpackages/<itemType>/*/*.js
    // for jobs and widgets
    fs.readdir(itemDir, function (err, items) {
      if (err) {
        return cb(err);
      }

      var selectedItems = [];
      items.forEach(function (item_name) {
        var item = path.join(itemDir, item_name);
        var stat = fs.statSync(item);
        if (stat.isDirectory()) {
          // /job/job1/job1.js
          item = path.join(item, item_name + extension);
        }

        if (path.extname(item) === extension) {
          if (fs.existsSync(item)) {
            selectedItems.push(item);
          }
        }
      });

      if (filters[itemType]) { // change to use custom filters for itemType
        selectedItems = selectedItems.filter(filters[itemType]);
      }

      package.items = selectedItems;
      return cb(null, package);
    });
  }


  // this function read all the packages from the provided directory packagesPath:
  // - packages/default/*
  // - packages/otherpackages/*
  // and calls readItemsFromPackageDir for every one of them

  function fillPackages(packagesPath, cb) {
    fs.readdir(packagesPath, function (err, allPackagesDir) {
      if (err) {
        return cb(err);
      }

      // convert to absolute path
      allPackagesDir = allPackagesDir.map(function (partialDir) {
        return path.join(packagesPath, partialDir);
      });

      // get only valid directories
      allPackagesDir = allPackagesDir.filter(function (dir) {
        return fs.statSync(dir).isDirectory();
      });

      // read items from every package and flatten results
      async.map(allPackagesDir, readItemsFromPackageDir, function (err, results) {
        if (err) {
          return cb(err);
        }
        cb(null, _.flatten(results));
      });
    });
  }

  // process all package paths
  async.map(packagesPath.filter(fs.existsSync), fillPackages, function (err, results) {
    if (err) {
      return callback(err);
    }
    callback(null, _.flatten(results));
  });
}
```
- example usage
```shell
...
 *
 * @param {[string]} packagesPath : list of directories to find packages in.
 * @param {string} itemType item type in plural. ('dashboards', 'jobs', 'widgets')
 * @param {string} extension : filter result by extension
 */

get: function (packagesPath, itemType, extension, callback) {
  this.getByPackage(packagesPath, itemType, extension, function (err, results) {
    if (err) {
      return callback(err);
    }
    var items = [];
    results.forEach(function (package) {
      items = items.concat(package.items);
    });
...
```

#### <a name="apidoc.element.atlasboard.item_manager.getFirst"></a>[function <span class="apidocSignatureSpan">atlasboard.item_manager.</span>getFirst (packagesPath, itemName, itemType, extension, callback)](#apidoc.element.atlasboard.item_manager.getFirst)
- description and source-code
```javascript
getFirst = function (packagesPath, itemName, itemType, extension, callback) {
  var thiz = this;
  this.get(packagesPath, itemType, extension, function (err, items) {
    if (err) {
      return callback(err);
    }

    var candidates = thiz.resolveCandidates(items, itemName, itemType, extension);
    callback(null, candidates.length ? candidates[0] : null);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.atlasboard.item_manager.resolveCandidates"></a>[function <span class="apidocSignatureSpan">atlasboard.item_manager.</span>resolveCandidates (items, name, itemType, extension)](#apidoc.element.atlasboard.item_manager.resolveCandidates)
- description and source-code
```javascript
resolveCandidates = function (items, name, itemType, extension) {
  var searchCriteria = "";
  if (name.indexOf("#") > -1) {
    var packageName = name.split("#")[0];
    var itemParsedName = name.split("#")[1];
    // package/jobs/job1/job1.js
    searchCriteria = path.join(packageName, this.resolveLocation(itemParsedName, itemType, extension));
  }
  else {
    // jobs/job1/job1.js
    searchCriteria = this.resolveLocation(name, itemType, extension);
  }

  searchCriteria = path.sep + searchCriteria;

  return items.filter(function (item) {
    return item.indexOf(searchCriteria) > -1;
  });
}
```
- example usage
```shell
...
getFirst: function (packagesPath, itemName, itemType, extension, callback) {
  var thiz = this;
  this.get(packagesPath, itemType, extension, function (err, items) {
    if (err) {
      return callback(err);
    }

    var candidates = thiz.resolveCandidates(items, itemName, itemType, extension);
    callback(null, candidates.length ? candidates[0] : null);
  });
},


/**
 * Return list of items found in any package within packagesPath
...
```

#### <a name="apidoc.element.atlasboard.item_manager.resolveLocation"></a>[function <span class="apidocSignatureSpan">atlasboard.item_manager.</span>resolveLocation (name, itemType, extension)](#apidoc.element.atlasboard.item_manager.resolveLocation)
- description and source-code
```javascript
resolveLocation = function (name, itemType, extension) {
  var useDirectoryLevel = ((itemType === "widgets") || (itemType === "jobs"));
  if (useDirectoryLevel) {
    // jobs/job1/job1.js
    return path.join(itemType, name, name + extension);
  }
  else {
    // dashboards/dashboard.json
    return path.join(itemType, name + extension);
  }
}
```
- example usage
```shell
...

  resolveCandidates: function (items, name, itemType, extension) {
var searchCriteria = "";
if (name.indexOf("#") > -1) {
  var packageName = name.split("#")[0];
  var itemParsedName = name.split("#")[1];
  // package/jobs/job1/job1.js
  searchCriteria = path.join(packageName, this.resolveLocation(itemParsedName, itemType, extension));
}
else {
  // jobs/job1/job1.js
  searchCriteria = this.resolveLocation(name, itemType, extension);
}

searchCriteria = path.sep + searchCriteria;
...
```



# <a name="apidoc.module.atlasboard.job_initialiser"></a>[module atlasboard.job_initialiser](#apidoc.module.atlasboard.job_initialiser)

#### <a name="apidoc.element.atlasboard.job_initialiser.init"></a>[function <span class="apidocSignatureSpan">atlasboard.job_initialiser.</span>init (options, cb)](#apidoc.element.atlasboard.job_initialiser.init)
- description and source-code
```javascript
function init(options, cb) {

  jobsManager.getJobs(options, function (err, jobWorkers) {
    if (err) {
      return cb(err);
    }

    var globalAuth = loadGlobalAuth(configManager('auth').authenticationFilePath);

    if (!jobWorkers.length) {
      logger.warn("No jobs found matching the current configuration and filters");
    }
    else {
      var eventQueue = new EventQueue(options.deps.io);
      jobWorkers.forEach(function (jobWorker, index) {

        // unique id for this widget in the wallboard
        jobWorker.id = jobWorker.dashboard_name + '-' +
            (jobWorker.widget_item.r || jobWorker.widget_item.row) + '-' +
            (jobWorker.widget_item.c || jobWorker.widget_item.col);

        jobWorker.pushUpdate = function (data) {
          eventQueue.send(jobWorker.id, data);
        };

        // add security info
        jobWorker.config.globalAuth = globalAuth;

        if (jobWorker.widget_item.enabled !== false) {

          jobDependencyManager.fillDependencies(jobWorker, options.deps);

          if (jobWorker.onInit) {
            jobWorker.onInit.call(jobWorker, jobWorker.config, jobWorker.dependencies);
          }

          if (jobWorker.onRun) {
            setTimeout(function () {
              var scheduler = new Scheduler(jobWorker);
              scheduler.start();
            }, index * 1500); // avoid a concurrency peak on startup
          }
        }
        else { // job is disabled
          jobWorker.pushUpdate({error: 'disabled'});
        }

      });
    }
    return cb();
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.atlasboard.job_manager"></a>[module atlasboard.job_manager](#apidoc.module.atlasboard.job_manager)

#### <a name="apidoc.element.atlasboard.job_manager.getJobs"></a>[function <span class="apidocSignatureSpan">atlasboard.job_manager.</span>getJobs (options, callback)](#apidoc.element.atlasboard.job_manager.getJobs)
- description and source-code
```javascript
getJobs = function (options, callback) {

  var packagesPath = options.packagesPath;
  var filters = options.filters || {};

  var configPath = path.join(options.configPath,"/dashboard_common.json");
  var generalDashboardConfig = {};

  var jobs = [];

  // ----------------------------------------------
  // general config is optional, but if it exists it needs to be a valid file
  // ----------------------------------------------
  if (fs.existsSync(configPath)){
    try{
      generalDashboardConfig = JSON.parse(fs.readFileSync(configPath)).config;
      if (!generalDashboardConfig) {
        throw 'invalid format. config property not found';
      }
    }
    catch (e){
      return callback("ERROR reading general config file..." + configPath);
    }
  }

  // ----------------------------------------------
  // get all dashboards from all packages folder
  // ----------------------------------------------
  itemManager.get(packagesPath, "dashboards", ".json", function(err, dashboardConfigFiles){
    if (err){ return callback(err); }

    // ----------------------------------------------
    // get all jobs from those packages
    // ----------------------------------------------
    itemManager.get(packagesPath, "jobs", ".js", function(err, allJobs){
      if (err){ return callback(err); }

      for (var d = 0, dl = dashboardConfigFiles.length; d < dl ; d++) {
        var dashboardName = dashboardConfigFiles[d];

        if (filters.dashboardFilter){
          if (!matchDashboardFilter(dashboardName, filters.dashboardFilter)){
            continue;
          }
        }

        var dashboardConfig;
        var dashboardJobs;
        try {
          dashboardConfig = readDashboard(dashboardName);
          dashboardJobs = processDashboard(allJobs, dashboardName, dashboardConfig, filters);
        }
        catch (e){
          return callback (e);
        }

        // add config to job, extending for the same config key in general config, if any
        dashboardJobs = dashboardJobs.map(function(job){
          // Multiple configurations:
          //  local overrides global
          //  config n+1 overrides config n
          if (Array.isArray(job.configKey)) {
            var configs = job.configKey.map(function(key){
              return extend(generalDashboardConfig[key], dashboardConfig.config[key]);
            });
            job.config = extend.apply(null, configs);
          } else { // single configuration
            job.config = extend(generalDashboardConfig[job.configKey], dashboardConfig.config[job.configKey]);
          }

          return job;
        });

        jobs = jobs.concat(dashboardJobs);
      }

      callback(null, jobs);
    });
  });
}
```
- example usage
```shell
...
var jobDependencyManager = require('./job-dependencies/loader.js');
var logger = require('./logger')();

exports = module.exports = (function () {

  function init(options, cb) {

    jobsManager.getJobs(options, function (err, jobWorkers) {
if (err) {
  return cb(err);
}

var globalAuth = loadGlobalAuth(configManager('auth').authenticationFilePath);

if (!jobWorkers.length) {
...
```



# <a name="apidoc.module.atlasboard.package_dependency_manager"></a>[module atlasboard.package_dependency_manager](#apidoc.module.atlasboard.package_dependency_manager)

#### <a name="apidoc.element.atlasboard.package_dependency_manager.installDependencies"></a>[function <span class="apidocSignatureSpan">atlasboard.package_dependency_manager.</span>installDependencies (packagesPath, callback)](#apidoc.element.atlasboard.package_dependency_manager.installDependencies)
- description and source-code
```javascript
installDependencies = function (packagesPath, callback){

  // Process all available package containers
  async.map (packagesPath.filter(fs.existsSync), checkPackagesFolder, function(err, results){
    if (err){ return callback(err); }
    var paths = _.flatten(results);

    async.eachSeries(paths, checkValidIfAtlasboardVersionForPackage, function (err){
      if (err){
        return callback(err);
      }

      async.eachSeries(paths, install, function (err){
        callback(err);
      });
    });
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.atlasboard.path_resolver"></a>[module atlasboard.path_resolver](#apidoc.module.atlasboard.path_resolver)

#### <a name="apidoc.element.atlasboard.path_resolver.fromAtlasboard"></a>[function <span class="apidocSignatureSpan">atlasboard.path_resolver.</span>fromAtlasboard ()](#apidoc.element.atlasboard.path_resolver.fromAtlasboard)
- description and source-code
```javascript
fromAtlasboard = function () {
  return getFromRootPath(__dirname, arguments);
}
```
- example usage
```shell
...
var debug = require('debug')('theming');

exports = module.exports = (function () {

var themingConfig = configManager('theming');

var localTheme = pathResolver.fromLocalWallboard('themes', themingConfig.theme, 'variables.styl');
var atlasboardTheme = pathResolver.fromAtlasboard('../themes', themingConfig.theme, 'variables.styl');

var defaultTheme = pathResolver.fromAtlasboard('../assets', 'stylesheets', 'variables.styl');

function getStylusObject(str) {
  var stylObj = stylus(str);
  stylObj.import(defaultTheme); // import default core stylus variables
...
```

#### <a name="apidoc.element.atlasboard.path_resolver.fromLocalWallboard"></a>[function <span class="apidocSignatureSpan">atlasboard.path_resolver.</span>fromLocalWallboard ()](#apidoc.element.atlasboard.path_resolver.fromLocalWallboard)
- description and source-code
```javascript
fromLocalWallboard = function () {
  return getFromRootPath(process.cwd(), arguments);
}
```
- example usage
```shell
...
var pathResolver = require('./path-resolver');
var debug = require('debug')('theming');

exports = module.exports = (function () {

var themingConfig = configManager('theming');

var localTheme = pathResolver.fromLocalWallboard('themes', themingConfig.theme, 'variables.styl');
var atlasboardTheme = pathResolver.fromAtlasboard('../themes', themingConfig.theme, 'variables.styl');

var defaultTheme = pathResolver.fromAtlasboard('../assets', 'stylesheets', 'variables.styl');

function getStylusObject(str) {
  var stylObj = stylus(str);
  stylObj.import(defaultTheme); // import default core stylus variables
...
```



# <a name="apidoc.module.atlasboard.scheduler"></a>[module atlasboard.scheduler](#apidoc.module.atlasboard.scheduler)

#### <a name="apidoc.element.atlasboard.scheduler.scheduler"></a>[function <span class="apidocSignatureSpan">atlasboard.</span>scheduler (jobWorker)](#apidoc.element.atlasboard.scheduler.scheduler)
- description and source-code
```javascript
function Scheduler(jobWorker) {
  this.jobWorker = ensureSafeJobWorkerConfiguration(jobWorker);
  this.originalInterval = jobWorker.config.interval;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.atlasboard.scheduler.prototype"></a>[module atlasboard.scheduler.prototype](#apidoc.module.atlasboard.scheduler.prototype)

#### <a name="apidoc.element.atlasboard.scheduler.prototype.scheduleNext"></a>[function <span class="apidocSignatureSpan">atlasboard.scheduler.prototype.</span>scheduleNext ()](#apidoc.element.atlasboard.scheduler.prototype.scheduleNext)
- description and source-code
```javascript
scheduleNext = function (){
  var self = this;
  setTimeout(function(){
    self.start();
  }, this.jobWorker.config.interval);
}
```
- example usage
```shell
...

    if (err) {
      handleError(err);
    }
    else {
      handleSuccess(data);
    }
    self.scheduleNext();
  }

  job.onRun.call(job, job.config, job.dependencies, jobCallback);

}
catch (e) {
  job.dependencies.logger.error('Uncaught exception executing job: ' + e);
...
```

#### <a name="apidoc.element.atlasboard.scheduler.prototype.start"></a>[function <span class="apidocSignatureSpan">atlasboard.scheduler.prototype.</span>start ()](#apidoc.element.atlasboard.scheduler.prototype.start)
- description and source-code
```javascript
start = function () {

  var self = this;
  var job = self.jobWorker;

  function handleError(err) {

    job.dependencies.logger.error('executed with errors: ' + err);

    // in case of error retry in one third of the original interval or 1 min, whatever is lower
    job.config.interval = Math.min(self.originalInterval / 3, 60000);

    // -------------------------------------------------------------
    // Decide if we hold error notification according to widget config.
    // if the retryOnErrorTimes property found in config, the error notification
    // won´t be sent until we reach that number of consecutive errrors.
    // This will prevent showing too many error when connection to flaky, unreliable
    // servers.
    // -------------------------------------------------------------
    var sendError = true;
    if (job.firstRun === false) {
      if (job.config.retryOnErrorTimes) {
        job.retryOnErrorCounter = job.retryOnErrorCounter || 0;
        if (job.retryOnErrorCounter <= job.config.retryOnErrorTimes) {
          job.dependencies.logger.warn('widget with retryOnErrorTimes. attempts: ' +
              job.retryOnErrorCounter);
          sendError = false;
          job.retryOnErrorCounter++;
        }
      }
    }
    else {
      // this is the first run for this job so if it fails, we want to inform immediately
      // since it may be a configuration or dev related problem.
      job.firstRun = false;
    }

    if (sendError) {
      job.pushUpdate({error: err, config: {interval: job.config.interval}});
    }
  }

  function handleSuccess(data) {
    job.retryOnErrorCounter = 0; //reset error counter on success
    job.dependencies.logger.log('executed OK');
    job.config.interval = self.originalInterval;
    if (!data) {
      data = {};
    }
    data.config = {interval: job.config.interval}; // give access to interval to client
    job.pushUpdate(data);
  }

  try {

    var cbCalled = false; // job_callback is meant to be executed only once per job run

    function jobCallback (err, data){
      if (cbCalled) {
        job.dependencies.logger.warn('WARNING!!!!: job_callback executed more than once for job ' +
        job.widget_item.job + ' in dashboard ' + job.dashboard_name);
      }
      cbCalled = true;

      if (err) {
        handleError(err);
      }
      else {
        handleSuccess(data);
      }
      self.scheduleNext();
    }

    job.onRun.call(job, job.config, job.dependencies, jobCallback);

  }
  catch (e) {
    job.dependencies.logger.error('Uncaught exception executing job: ' + e);
    handleError(e);
    self.scheduleNext();
  }
}
```
- example usage
```shell
...
  if (jobWorker.onInit) {
    jobWorker.onInit.call(jobWorker, jobWorker.config, jobWorker.dependencies);
  }

  if (jobWorker.onRun) {
    setTimeout(function () {
      var scheduler = new Scheduler(jobWorker);
      scheduler.start();
    }, index * 1500); // avoid a concurrency peak on startup
  }
}
else { // job is disabled
  jobWorker.pushUpdate({error: 'disabled'});
}
...
```



# <a name="apidoc.module.atlasboard.stylus"></a>[module atlasboard.stylus](#apidoc.module.atlasboard.stylus)

#### <a name="apidoc.element.atlasboard.stylus.getMiddleware"></a>[function <span class="apidocSignatureSpan">atlasboard.stylus.</span>getMiddleware (options)](#apidoc.element.atlasboard.stylus.getMiddleware)
- description and source-code
```javascript
getMiddleware = function (options) {
  return stylus.middleware({
    src: options.src,
    dest: options.dest,

    compile: function (str, filePath) {
      var stylObj = getStylusObject(str);
      stylObj.set('filename', filePath)
          .set('warn', false)
          .set('compress', true)
          .use(nib());

      return stylObj;
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.atlasboard.stylus.getWidgetCSS"></a>[function <span class="apidocSignatureSpan">atlasboard.stylus.</span>getWidgetCSS (str, cb)](#apidoc.element.atlasboard.stylus.getWidgetCSS)
- description and source-code
```javascript
getWidgetCSS = function (str, cb) {
  getStylusObject(str).render(cb);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.atlasboard.template_manager"></a>[module atlasboard.template_manager](#apidoc.module.atlasboard.template_manager)

#### <a name="apidoc.element.atlasboard.template_manager.resolveTemplateLocation"></a>[function <span class="apidocSignatureSpan">atlasboard.template_manager.</span>resolveTemplateLocation (fileName, cb)](#apidoc.element.atlasboard.template_manager.resolveTemplateLocation)
- description and source-code
```javascript
resolveTemplateLocation = function (fileName, cb) {
  var localWallboardLocation = path.join(process.cwd(), "templates", fileName);
  var defaultAtlasboardLocation = path.join(__dirname, "../templates", fileName);
  fs.exists(localWallboardLocation, function(exists){
    if (exists) {
      cb(null, localWallboardLocation);
    }
    else {
      cb(null, defaultAtlasboardLocation);
    }
  });
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
