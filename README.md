[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/mozilla/code-coverage) 

[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/mozilla/code-coverage) 

# Mozilla Code Coverage

This project has 4 parts:

* `bot` is a Python script running as a Taskcluster hook, aggregating code coverage data from Mozilla repositories,
* `backend` is a Python API built with Flask, that serves the aggregated code coverage data, in an efficient way,
* `frontend` is a vanilla Javascript SPA displaying code coverage data in your browser,
* `addon` is a Web Extension for Firefox, extending several Mozilla websites with code coverage data.
