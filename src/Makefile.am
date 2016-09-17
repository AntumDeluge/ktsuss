bin_PROGRAMS = ktsuss

ktsuss_SOURCES = errors.h ktsuss.c su_backend.c su_backend.h sudo_backend.c sudo_backend.h
ktsuss_LDADD = $(DEPS_LIBS) -lutil
AM_CPPFLAGS = $(DEPS_CFLAGS) -DPIXMAPS=\""$(datadir)/pixmaps"\"
