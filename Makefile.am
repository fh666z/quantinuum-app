AUTOMAKE_OPTIONS = foreign

ACLOCAL_AMFLAGS = -I m4

CFLAGS = -Wall -pedantic
include_HEADERS = quantinuumapp.h

lib_LTLIBRARIES = libquantinuum.la
libquantinuum_la_SOURCES  = quantinuumlib.c
libquantinuum_la_LDFLAGS= -version-info 1:0:0

bin_PROGRAMS = quantinuumapp
quantinuumapp_SOURCES = quantinuumapp.c
quantinuumapp_LDADD = .libs/libquantinuum.la
