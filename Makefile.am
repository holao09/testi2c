AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic -O2 --version-script=i2c/libi2c.map
include_HEADERS = i2c/smbus.h

lib_LTLIBRARIES = libi2cmeta.la
libi2cmeta_la_SOURCES  = i2c/smbus.c
libi2cmeta_la_LDFLAGS= -version-info 1:0:0

bin_PROGRAMS = i2cexample
bbexample_SOURCES = i2cexample.c
bbexample_LDADD = libi2cmeta.la
