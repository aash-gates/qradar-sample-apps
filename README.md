# QRadar sample apps

This repository holds a number of QRadar sample apps, built using v2 of the QRadar App Framework. These apps are
based on the Red Hat Universal Base Image, not the old CentOS 6 app image.

## Using these samples

To use the samples it is recommended you have the QRadar App SDK v2 installed, which allows you to bundle apps through
its command line interface and deploy them to QRadar, or even run the apps locally.

Some apps require dependencies to be pulled down (if so it is explained in the apps' README), to pull down the required
dependencies make sure you have the following installed:

- [Python 3](https://www.python.org/downloads/) and [pip](https://pip.pypa.io/en/stable/installing/) - To download
required Python modules.
- [Docker](https://docs.docker.com/get-docker/) - To download required Red Hat RPMs.

## Samples

- [Replacing Flask with an Alternative HTTP Server](./AlternativeHTTPServer)
- [Using the QPyLib Ariel features](./Ariel)
- [Running a command as root during app startup](./AsRoot)
- [Controlling browser cache](./CacheControl)
- [Using QPyLib to encrypt values](./Encryption)
- [Replacing Flask with Gunicorn](./Gunicorn)
- [Simple 'hello world' app](./HelloWorld)
- [Designating how much memory an app needs](./Memory)
- [App that supports multi-tenancy](./Multitenancy)
- [App that uses NGINX rather than Flask](./NGINX)
- [App that retrieves proxy values](./Proxy)
- [QJSLib imported through the browser](./QJSLibBrowser)
- [QJSLib imported through NPM](./QJSLibNPM)
- [App that allows user submitted QRadar Vulnerability Manager scans](./QuickScan)
- [App that uses a REST method to populate a Dashboard Item](./RESTMethod)

## Project details

- [CONTRIBUTING](CONTRIBUTING.md)
- [MAINTAINERS](MAINTAINERS.md)
