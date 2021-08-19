include $(top_srcdir)/build/modmake.rulesam
MODNAME=mod_event_redis

mod_LTLIBRARIES = mod_event_redis.la
mod_event_redis_la_SOURCES  = mod_event_redis.cpp
mod_event_redis_la_CFLAGS   = $(AM_CFLAGS)
mod_event_redis_la_LIBADD   = $(switch_builddir)/libfreeswitch.la
mod_event_redis_la_CXXFLAGS = -fPIC -g -ggdb -I/usr/include  $(AM_CXXFLAGS) -std=c++1y
mod_event_redis_la_LDFLAGS  = -avoid-version -module -no-undefined -shared -lcpp_redis -ltacopie  -lz -lpthread -lrt -lssl
