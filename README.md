skag
====

A simple tool for Certificate Authority style management of ssh host and user keys

### usage ###

Sign a server's host key:

    skag [OPTIONS] -H HOSTNAME "HOST KEY FILE"

Sign a user's key:

    skag [OPTIONS] -U USERNAME -F "FULL NAME" "USER KEY FILE"

### options ###

    -c FILE               use this config file
    -s FILE               use this signing key
    -U USERNAME           sign this user's key
    -H HOSTNAME           sign this host's key


skag-setup
==========

A setup assistant for skag

### usage ###

Set up a skag ssh certificate authority:

    skag-setup [OPTIONS]

### options ###

    -H DIRECTORY     skag home directory
    -c FILE          write this config file
    -s FILE          use (or generate) this signing key
