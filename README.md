# cucumber-electron 

Runs cucumber-js in an electron renderer process, meaning cucumber scenarios
have direct access to both a browser DOM and node.js stuff.

[![Build Status](https://travis-ci.org/featurist/cucumber-electron.svg?branch=master)](https://travis-ci.org/featurist/cucumber-electron)

## Usage

Use it like cucumber-js:
```
cucumber-electron ./example/features/hello.feature:2
```

## Debugging

The `--electron-debug` command line switch shows the browser window and keeps
it open after all features have been run.
