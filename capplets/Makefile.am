SUBDIRS = \
	common \
	accessibility \
	appearance \
	default-applications \
	display \
	keyboard \
	keybindings \
	mouse \
	network \
	windows \
	about-me

DIST_SUBDIRS = \
	common \
	accessibility \
	appearance \
	default-applications \
	keybindings \
	keyboard \
	mouse \
	network \
	windows \
	display \
	about-me

if HAVE_POLKIT
SUBDIRS += time-admin
DIST_SUBDIRS += time-admin
endif

-include $(top_srcdir)/git.mk
