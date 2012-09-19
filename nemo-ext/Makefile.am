
INCLUDES = -I$(top_builddir) 	\
	-I$(top_srcdir) 			\
	$(NEMO_CFLAGS) 			\
	-DGNOMELOCALEDIR=\""$(datadir)/locale"\"

nemo_extensiondir=$(NEMO_EXTENSION_DIR)

nemo_extension_LTLIBRARIES=libnemo-seahorse.la

libnemo_seahorse_la_SOURCES =     \
        seahorse-nemo.c           \
        seahorse-nemo.h           \
        seahorse-nemo-module.c

libnemo_seahorse_la_LDFLAGS = -module -avoid-version -no-undefined
libnemo_seahorse_la_LIBADD  = $(NEMO_LIBS)
