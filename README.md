# wordpress-docker
Boilerplate for a local Wordpress dev environment

## Usage
Start: `docker-compose up -d`

Stop: `docker-compose down`

Bash shell: `docker-compose exec wordpress /bin/bash`

MySQL: `docker-compose exec db mysql --user=wordpressuser --password=58BNnYZuC2v&S5 wordpressdb`

## Useful docker commands

Docker stop all containers

`docker container stop $(docker container ls -aq)`


Docker remove all containers 

`docker container rm $(docker container ls -aq)`


# Install WP CLI

(Run inside bash shell)

curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar