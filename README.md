skag
====

A simple tool for Certificate Authority style management of ssh host and user keys

### usage ###

  skag [<options>] -H <hostname> <host key file>
  skag [<options>] -U <username> -F "<full name>" <user key file>

### options ###
  -c <config file>     use this config file
  -s <signing key>     use this signing key
  -U <username>        sign this user's key
  -H <hostname>        sign this host's key

skag-setup
==========

A setup assistant for skag

### usage ###

  skag-setup [<options>]

### options ###
  -H <directory>     skag home directory
  -c <file>          write this config file
  -s <file>          use (or generate) this signing key