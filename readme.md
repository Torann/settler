# Laravel Settler

The scripts that build the Laravel Homestead development environment. 

End result can be found at https://app.vagrantup.com/torann/boxes/homestead

## Usage

You probably don't want this repo, follow instructions at https://github.com/Torann/homestead instead.

If you know what you are doing:

- Clone [chef/bento](https://github.com/chef/bento) into same top level folder as this repo.
- Run `./bin/link-to-bento.sh`
- Run `cd ../bento` and work there for the remainder.
- Follow normal [Packer](https://www.packer.io/) practice of building:

```
cd ubuntu
packer build -only=virtualbox-iso ubuntu-18.04-amd64.json
```

## Included

- Ubuntu 18.04
- Git
- PHP 7.3
- Nginx
- MySQL
- [lmm](https://github.com/Lullabot/lmm) for MySQL or MariaDB database snapshots
- Sqlite3
- PostgreSQL
- PostGIS
- Composer
- Node (With Yarn, Bower, Grunt, and Gulp)
- Redis
- PHPRedis
- [Phpiredis](https://github.com/nrk/phpiredis)
- Memcached
- Beanstalkd
- [Mailhog](https://github.com/mailhog/MailHog)
- avahi
- ngrok
- Xdebug
- [XHProf](https://github.com/phacility/xhprof) / [Tideways](https://tideways.com/) / [XHGui](https://github.com/perftools/xhgui)
- [Minio](https://github.com/minio/minio)
- [wkhtmltopdf](https://github.com/wkhtmltopdf/wkhtmltopdf/releases)
