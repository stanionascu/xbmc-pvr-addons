#
# Makefile for the PVR Kartina TV add-on for Kodi PVR
#
# See the README for copyright information and
# how to reach the author.
#

ADDONBINNAME    = Kodi_KartinaTV
ADDONNAME       = pvr.kartinatv
LIBNAME         = libpvrkartinatv-addon
lib_LTLIBRARIES = libpvrkartinatv-addon.la

LIBS            = @abs_top_srcdir@/lib/jsoncpp/libjsoncpp.la

include ../Makefile.include.am

AM_CPPFLAGS+=-I@abs_top_srcdir@/lib/jsoncpp/include

libpvrdemo_addon_la_SOURCES = src/client.cpp \
                              src/kartinatvclient.cpp
libpvrdemo_addon_la_LDFLAGS = @TARGET_LDFLAGS@

