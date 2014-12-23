GENERATED_FILES =					\
	PlugUSB.sym					\
	PIC16F1454.sym					\
	TCS3200.sym

designsymbolsdir = $(datadir)/colorhug-hardware/symbols
designsymbols_DATA =					\
	${GENERATED_FILES}

all: ${GENERATED_FILES}

%.sym: %.tsym
	${TRAGESYM} $< $@

CLEANFILES =						\
	${GENERATED_FILES}

EXTRA_DIST = ${designsymbols_DATA}

-include $(top_srcdir)/git.mk
