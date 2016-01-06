This is meant to be a list of utility functions and scripts that make working with and developing drupal easier.

This is for all of those little helper utilities you have that make developing locally easier.

Expectations
---
You can create an ssh key and add it to authorized users as needed
You are familiar with adding a command to your path
You have access to a user that can access remote servers and execute the necessary commands

PULL requests welcome

TODO
write examples
write necessary changes to remote server

server_backup
---
mysqlbackup
connects to a server and creates a local export of all of the mysql databases locally

filersync
connects to a server and syncs the filesystem to local

archiver
archives local backups allowing for weekly/monthly backups

local_development
---
new_site
sets up local apache virtualhost and connects to a codebase: requires sudo

remove_site
removes apache virtualhost
