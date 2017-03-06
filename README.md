## Install

[![Build Status](https://travis-ci.org/RallyApps/fetch-github-repo.png?branch=master)](https://travis-ci.org/RallyApps/fetch-github-repo)

`npm install rally-fetch-github-repo`

## API

JavaScript
```
var FetchGithubRepo, callback;

FetchGithubRepo = require("rally-fetch-github-repo");

callback = function(err) {};

FetchGithubRepo.download({
  organization: 'RallyApps',
  repo: "fetch-github-repo",
  path: "."
}, callback);

```


Coffee
```
FetchGithubRepo = require "rally-fetch-github-repo"
callback = (err)->
FetchGithubRepo.download
  organization: 'RallyApps'
  repo : "fetch-github-repo",
  path: "."
  callback
```


## Run Tests

To run the tests:
npm test
