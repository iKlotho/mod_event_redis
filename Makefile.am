include $(top_srcdir)/build/modmake.rulesam
MODNAME=mod_event_redis

mod_LTLIBRARIES = mod_skel.la
mod_skel_la_SOURCES  = mod_skel.cpp
mod_amd_la_CFLAGS   = $(AM_CFLAGS) $(AM_MOD_amd_CXXFLAGS)
mod_skel_la_LIBADD   = $(switch_builddir)/libfreeswitch.la
mod_skel_la_LDFLAGS  = -avoid-version -module -no-undefined -shared
