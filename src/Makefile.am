lib_LTLIBRARIES = libsymspg.la

spglib_c = \
arithmetic.c \
cell.c \
debug.c \
delaunay.c \
determination.c \
hall_symbol.c \
kgrid.c \
kpoint.c \
mathfunc.c \
niggli.c \
overlap.c \
pointgroup.c \
primitive.c \
refinement.c \
site_symmetry.c \
sitesym_database.c \
spacegroup.c \
spg_database.c \
spglib.c \
spin.c \
symmetry.c

spglib_h = \
arithmetic.h \
cell.h \
debug.h \
delaunay.h \
determination.h \
hall_symbol.h \
kgrid.h \
kpoint.h \
mathfunc.h \
niggli.h \
overlap.h \
pointgroup.h \
primitive.h \
refinement.h \
site_symmetry.h \
sitesym_database.h \
spacegroup.h \
spg_database.h \
spglib.h \
spin.h \
symmetry.h \
version.h

libsymspg_la_SOURCES = $(spglib_c) $(spglib_h)
pkginclude_HEADERS = $(spglib_h)
# libsymspg_la_LDFLAGS = -version-info 0:1:0
libsymspg_la_LIBADD = -lm

check_PROGRAMS = spglib_test
spglib_test_SOURCES = test.c $(spglib_c) $(spglib_h)
spglib_test_CFLAGS = $(AM_CFLAGS)
spglib_test_LDADD = -lm
#AM_DEFAULT_SOURCE_EXT = .c
TESTS = spglib_test
