# python-web-bottle-ssl-mvc-dolt-pop

## Description
Simple web app that serves static pages
for a bottle project.

Uses sqlalchemy query a table `pop`.

Is self-signed ssl cert.

## Tech stack
- python
  - bottle
  - sqlalchemy
  - cheroot
  - beaker
- bootstrap
- jquery
- dataTable
- dolthub/dolt-sql-serverdb
- ssl

## Docker stack
- alpine:edge
- python:latest
- dolthub/dolt-sql-serverdb:latest

## To run
`sudo ./install.sh -u`
- [Availble at](https://localhost)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Bottle sqlalchemy setup](https://github.com/iurisilvio/bottle-sqlalchemy/blob/master/examples/basic.py)
