# docker-ffa-wordpress
FFA docker image derived from wordpress and used for reports archive

Published at docker hub [here](https://hub.docker.com/r/shadiakiki1986/ffa-wordpress/)

To build locally
```
docker build -t shadiakiki1986/ffa-wordpress:local .
```

For run usage, check the `docker-compose.yml` file

# Features
* docker-compose file to launch wordpress and mysql database
* plugins installed:
 * Rest API
 * basic authorization

# TODO
* add seamless login via ldap
 * check [this](https://github.com/it-herz/docker-wordpress/blob/master/Dockerfile)
