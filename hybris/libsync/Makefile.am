lib_LTLIBRARIES = \
	libsync.la

libsync_la_SOURCES = sync.c
libsync_la_CFLAGS = -I$(top_srcdir)/include -I$(top_srcdir)/include/android
if WANT_TRACE
libsync_la_CFLAGS += -DDEBUG
endif
if WANT_DEBUG
libsync_la_CFLAGS += -ggdb -O0
endif
libsync_la_LDFLAGS = \
	-version-info "2":"0":"0"
