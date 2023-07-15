# new-javascript-web-htmx-mustache-python-flask-api-cockroachdb-multi-node-simple

## Description
A demo of htmx using a python flask
api to return contents of table from
a multi node cluster cockroachdb.

## Tech stack
- htmx
    - get
    - ext
    - swap
    - target
- mustache
- python
    - flask
    - cors
- cockroachdb

## Docker stack
- httpd:latest
- python:latest
- cockroachdb/cockroach:v19.2.4

## To run
`sudo ./install.sh -u`
- Available at http://localhost

## To stop
`sudo ./install.sh -d`

## To see help
`sudo ./install.sh -h`

## Credit
- [Htmx clientside template](https://htmx.org/extensions/client-side-templates/)
- [Htmx rendering JSON](https://marcus-obst.de/blog/htmx-json-handling)