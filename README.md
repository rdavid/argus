# Argus
Configures, builds and runs external server.

[![Hits-of-Code](https://hitsofcode.com/github/rdavid/argus?branch=master)](https://hitsofcode.com/view/github/rdavid/argus?branch=master)
[![License](https://img.shields.io/badge/license-0BSD-green)](https://github.com/rdavid/argus/blob/master/LICENSE)

* [About](#about)
* [Install](#install)
* [License](#license)

## About
Hi, I'm [David Rabkin](http://cv.rabkin.co.il).

The server runs Transmission, OpenVPN, Ngnix.

## Install

    git clone https://github.com/rdavid/argus.git && cd argus
    cat <<EOT >> cred.env
    USER=[username]
    PASS=[password]
    EOT
    sudo docker-compose up -d

## License
The scripts are copyright [David Rabkin](http://cv.rabkin.co.il) and available
under a [Zero-Clause BSD license](https://github.com/rdavid/argus/blob/master/LICENSE).

