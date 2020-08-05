## Process this file with automake to produce Makefile.in

## Created by Anjuta

AM_CPPFLAGS = \
	-DPACKAGE_LOCALE_DIR=\""$(localedir)"\" \
	-DPACKAGE_SRC_DIR=\""$(srcdir)"\" \
	-DPACKAGE_DATA_DIR=\""$(pkgdatadir)"\"

AM_CFLAGS =\
	 -Wall\
	 -g

bin_PROGRAMS = bank

bank_SOURCES = \
	main.c \
	banking.h \
	common.h \
	ipc.c \
	ipc.h \
	pa2345.h \
	process.h \
	bank_robbery.c \
	banking.c

bank_LDFLAGS = 

bank_LDADD =  \
	/home/linux/bank/src/libruntime.so

