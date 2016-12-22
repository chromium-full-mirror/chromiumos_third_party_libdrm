AM_CPPFLAGS = \
	-pthread \
	-I$(top_srcdir)/include/drm \
	-I$(top_srcdir)/nouveau \
	-I$(top_srcdir)

AM_CFLAGS = $(WARN_CFLAGS)

LDADD = \
	../../nouveau/libdrm_nouveau.la \
	../../libdrm.la \
	-ldl

TESTS = threaded

check_PROGRAMS = $(TESTS)

