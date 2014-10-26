ACLOCAL_AMFLAGS = -I m4 --install

lib_LTLIBRARIES = libwhine-1.0.la
libwhine_1_0_la_SOURCES = src/whine.c src/whine.h
libwhine_1_0_la_LDFLAGS = -version-info 0:0:0
include_HEADERS = src/whine.h

bin_PROGRAMS = hello
hello_SOURCES = src/hello.c
hello_LDADD = $(lib_LTLIBRARIES)

EXTRA_DIST = m4/NOTES
