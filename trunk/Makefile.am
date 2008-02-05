bin_PROGRAMS=gtknowa
gtknowa_SOURCES=gtknowa.c
AM_CPPFLAGS=-DDATA_DIR=\"$(pkgdatadir)\" -DLOCALE_DIR=\"$(datadir)/locale\"
INCLUDES=${GTK_CFLAGS}
gtknowa_LDADD=${GTK_LIBS}
dist_pkgdata_DATA=data/nowa.png data/loading.gif data/reload.png data/post.png data/home.png data/logo.png
EXTRA_DIST=gtknowa.spec
