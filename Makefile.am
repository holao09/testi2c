AUTOMAKE_OPTIONS = foreign
CFLAGS = -Wall -pedantic -O2
lib_LTLIBRARIES = libi2c-meta.la
libi2cmeta_la_SOURCES  = i2c/smbus.c
libi2cmeta_la_LDFLAGS= -version-info 1:0:0
bin_PROGRAMS = i2cexample
bbexample_SOURCES = i2cexample.c
bbexample_LDADD = libi2cmeta.la