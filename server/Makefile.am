##
## Copyright The University of Chicago
## All Rights Reserved.
##
SUBDIRS = src/pam src/config man/

oauthsshconfdir = $(sysconfdir)/oauth_ssh
oauthsshconf_DATA = data/globus-ssh.conf data/globus-acct-map

doc_DATA = data/oauth-ssh.te

EXTRA_DIST = $(oauthsshconf_DATA) $(doc_DATA)

ACLOCAL_AMFLAGS = -I m4
