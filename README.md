# Ostinato

[![Build Status](https://travis-ci.org/pstavirs/ostinato.svg?branch=master)](https://travis-ci.org/pstavirs/ostinato)

This is the code repository for the Ostinato network packet crafter and traffic generator

Visit https://ostinato.org for demo video and details

License: GPLv3+ (see [COPYING](https://raw.githubusercontent.com/pstavirs/ostinato/master/COPYING))

# How to build
$ qmake -project && qmake && make

# How to run after build
# Run 2 programs in order & simultaneously
$ sudo ./server/drone
$ ./client/ostinato
