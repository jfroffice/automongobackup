# Maintainance

* Please notice that this Project is not under current/heavy development
* If you would like to take ownership, get in contact with the maintainers

## Working with Docker

This script allow you to make a dump in the host from a running mongo container, you just need to set __DOCKER_LINK__ and __DOCKER_CONTAINER__

```
DOCKER_LINK="db_1:mongo"
DOCKER_CONTAINER="mongo:3.3"
```

## AutoMongoBackup

This is a very barebones port of the "AutoMySQLBackup":http://sourceforge.net/projects/automysqlbackup/ project. This bash script will allow you to do daily backups of a Mongo database. It includes periodic rotation so that you can keep historical weekly and monthly backups, as well as daily.

## License

This is released under GPL version 2.
