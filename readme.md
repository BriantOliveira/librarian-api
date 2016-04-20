# librarian-api [![Build Status](https://travis-ci.org/millette/librarian-api.svg?branch=master)](https://travis-ci.org/millette/librarian-api) [![Coverage Status](https://coveralls.io/repos/github/millette/librarian-api/badge.svg?branch=master)](https://coveralls.io/github/millette/librarian-api?branch=master)
> Client library for the libraries.io api.

## Install
```
$ npm install --save librarian-api
```

## Usage
```js
const librarianApi = require('librarian-api');

librarianApi('unicorns');
//=> 'unicorns & rainbows'
```

## Environment variables
You'll need a token from <https://libraries.io/account> to call the API.

Define it as an environment variable:

```sh
export LIBRARIES_IO_TOKEN=abcd1234...
```

If you use another instance of libraries.io, you can define it the
same way:

```sh
export LIBRARIES_IO_ENDPOINT=http://example.com/api
```

Otherwise https://libraries.io/api is used.


## API
API Docs: https://libraries.io/api

### librarianApi.search(query)
#### query
Type: `string`

Lorem ipsum.

### librarianApi.platform(platform, name)
#### platform
Type: `string`

#### name
Type: `string`

Lorem ipsum.

### librarianApi.platform.dependencies(platform, name, version)
#### platform
Type: `string`

#### name
Type: `string`

#### version
Type: `string`

Lorem ipsum.

### librarianApi.platform.dependents(platform, name)
#### platform
Type: `string`

#### name
Type: `string`

Lorem ipsum.

### librarianApi.platform.dependent_repositories(platform, name)
#### platform
Type: `string`

#### name
Type: `string`

Lorem ipsum.


### librarianApi.github(owner, name)
#### owner
Type: `string`

#### name
Type: `string`

Lorem ipsum.

### librarianApi.github.dependencies(owner, name)
#### owner
Type: `string`

#### name
Type: `string`

Lorem ipsum.

### librarianApi.github.projects(owner, name)
#### owner
Type: `string`

#### name
Type: `string`

Lorem ipsum.

## CLI
```
$ npm install --global librarian-api
```

```
$ librarian-api --help

  Usage
    librarian-api [input]

  Options
    --foo  Lorem ipsum. [Default: false]

  Examples
    $ librarian-api
    unicorns & rainbows
    $ librarian-api ponies
    ponies & rainbows
```


## License
AGPL-v3 © [Robin Millette](http://robin.millette.info)
