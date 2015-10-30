## this gets processed by "autoreconf --install" to create Makefile.in

SUBDIRS=	genoa

rpm: all
	env RPMDIR=/tmp epm_cover -a `uname -i` genoa

EXTRA_DIST = genoa.spec \
	genoa/genoa genoa/genoa.8 \
	templates \
	COPYRIGHT README

