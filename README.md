# Brunch React Skeleton

A Brunch skeleton for React.

## Features

* React
* Sass
* Auto-reload on save
* Brunch for building
* Bower for front component management
* Mocha testing

## Installation

```
brunch new gh:banyan/brunch-react-skelton
npm i
bower i
```

## Usage

### Run

```
brunch watch --server
```

### Build

```
brunch build
brunch build --production
```

### Test

Add test target file name at `test/initialize.coffee`

```
mocha-phantomjs public/test/index.html # or npm test (you need to build once before test)
```

# Credit

This is based on [warrenseine/brunch-react-less](https://github.com/warrenseine/brunch-react-less). Thanks.

# Contribute

`brunch-react-skelton` is MIT-licensed. Feel free to contribute.
