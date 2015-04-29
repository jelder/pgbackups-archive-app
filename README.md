# pgbackups-archive-app

A means to run `pgbackups-archive` without depending on a Rails app, which is in turn a means of automating Heroku PGBackups and archiving them to Amazon S3.

## Getting Started

First, deploy this app directly by clicking this button.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/jelder/pgbackups-archive-app)

This app is a trivial shell around [pgbackups-archive](https://github.com/kjohnston/pgbackups-archive), so you need to be familiar with it.