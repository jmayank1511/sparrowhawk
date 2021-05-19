if HAVE_BIN
bin_PROGRAMS = normalizer_main

AM_CPPFLAGS = -I$(srcdir)/../include

LDADD= ../lib/libsparrowhawk.la -L/usr/local/lib/fst -lthrax -lfstfar -lfst -lm -ldl -lprotobuf -lre2 -lglog -lgflags

normalizer_main_SOURCES = normalizer_main.cc
endif
