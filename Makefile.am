# Copyright (C) 2006 International Business Machines and others.
# All Rights Reserved.
# This file is distributed under the Eclipse Public License.

## $Id$

# Author:  Andreas Waechter           IBM    2006-04-13

AUTOMAKE_OPTIONS = foreign

########################################################################
#     List files that should be distributed and possibly cleaned       #
########################################################################

EXTRA_DIST = $(EXAMPLE_FILES) README AUTHORS LICENSE

DISTCLEANFILES = $(EXAMPLE_CLEAN_FILES)

datacoindir = $(datadir)/coin/Data/Infeas
datacoin_DATA = $(EXAMPLE_FILES)

coindocdir = $(datadir)/coin/doc/Data/Infeas
coindoc_DATA = README AUTHORS LICENSE

pkgconfiglibdir = $(libdir)/pkgconfig
pkgconfiglib_DATA = coindatainfeas.pc

include BuildTools/Makemain.inc
