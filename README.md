# Argus [![hits of code](https://hitsofcode.com/github/rdavid/argus?branch=master&label=hits%20of%20code)](https://hitsofcode.com/view/github/rdavid/argus?branch=master) [![license](https://img.shields.io/github/license/rdavid/argus?color=blue&labelColor=gray&logo=freebsd&logoColor=lightgray&style=flat)](https://github.com/rdavid/argus/blob/master/LICENSE)
Configures, builds, and runs an external server.

* [About](#about)
* [Install](#install)
* [License](#license)

## About
Hi, I'm [David Rabkin](http://cv.rabkin.co.il).

The server runs Transmission, OpenVPN, Ngnix.

## Install
```sh
git clone https://github.com/rdavid/argus.git
cd argus
cat <<EOT >> cred.env
USER=[username]
PASS=[password]
URL=[url]
EOT
sudo docker-compose up -d
```
## License
`argus` is copyright [David Rabkin](http://cv.rabkin.co.il) and available
under a [Zero-Clause BSD license](https://github.com/rdavid/argus/blob/master/LICENSE).

