# Custom LDAP Schema

This is an example how to create custom Schema in LDAP. You need familiarities with Docker and `docker-compose` command.

## How to run

1. Clone this repository and go to directory of this repository.
2. Run `docker-compose up -d`. It will be execute `docker-compose.yml` file.

Custom schema create in folder `docker/ldap` and bind with openldap volume when run `docker-compose up -d`.

You can check new attributes 'myadditionnalAttr' and 'myadditionnalAttr2' in LDAP client like [ldapclient.com](http://www.ldapclient.com/).

## Thanks

Philippe Andréas creates [How to : customized LDAP schema Docker image for a Symfony 4 project](https://medium.com/@philippe_andreas/how-to-customized-ldap-schema-docker-image-for-a-symfony-4-project-df6efc806867).