lib_LTLIBRARIES	=	libmdb.la
libmdb_la_SOURCES=	catalog.c mem.c file.c table.c data.c dump.c backend.c money.c sargs.c index.c like.c write.c stats.c map.c props.c worktable.c options.c iconv.c
libmdb_la_LDFLAGS = -version-info 2:1:0 -export-symbols-regex '^(mdb_|_mdb_put_int16$$|_mdb_put_int32$$)'
AM_CFLAGS	=	-I$(top_srcdir)/include $(GLIB_CFLAGS)
LIBS = $(GLIB_LIBS) @LIBS@ @LIBICONV@
