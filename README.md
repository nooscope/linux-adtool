## Description:
adtool is a unix command line utility for Active Directory administration.  Features include user and group creation, deletion, modification, password setting and directory query and search capabilities.

## System requirements:
adtool requires LDAP libraries to be installed (www.openldap.org).  To use secure (ldaps://) connections OpenLDAP has to have been built with SSL support.  SSL support is required for the password setting feature to work.

## Installation:
```
tar zxvf adtools-1.x.tar.gz
cd adtools-1.x
./configure
make
make install
```

Configure options: `--prefix=install_path`, `--with-ldap=/openldap_install_prefix`

## Configuration:
An example configuration file is installed to {prefix}/etc/adtool.cfg.dist.  Rename this to adtool.cfg and edit as appropriate.  Alternatively, command line options can be used.

## Usage:
See the adtool man page

