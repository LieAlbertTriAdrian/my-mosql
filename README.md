# My MoSQL

## Description
**My MoSQL** is an example of using MoSQL, an open source MongoDB → SQL streaming translator

## Install dependencies
`bundle install`

## Run command example
`mosql -c collections.yml --mongo mongodb://localhost:27017 --sql postgres://localhost:5432/albert_postgres --only-db albert`