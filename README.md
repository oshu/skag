skag
====

A simple tool for Certificate Authority style management of ssh host and user keys

### usage ###

    skag [OPTIONS] -H HOSTNAME "HOST KEY FILE"
    skag [OPTIONS] -U USERNAME -F "FULL NAME" "USER KEY FILE"

### options ###

* -c "CONFIG FILE"     use this config file
* -s "SIGNING KEY"     use this signing key
* -U USERNAME          sign this user's key
* -H HOSTNAME          sign this host's key


skag-setup
==========

A setup assistant for skag

### usage ###

    skag-setup [OPTIONS]

### options ###

* -H DIRECTORY     skag home directory
* -c FILE          write this config file
* -s FILE          use (or generate) this signing key
