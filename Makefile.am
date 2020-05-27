AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic -O2 
include_HEADERS = i2c/smbus.h

lib_LTLIBRARIES = libi2cmeta.la
libi2cmeta_la_SOURCES  = i2c/smbus.c
libi2cmeta_la_LDFLAGS= -version-info 1:0:0 --version-script=i2c/libi2c.map

bin_PROGRAMS = i2cexample
i2cexample_SOURCES = i2cexample.c
i2cexample_LDADD = libi2c.la
