# Copyright (C) 2005-2011 MaNGOS <http://getmangos.com/>
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA

## Process this file with automake to produce Makefile.in

## CPP flags for includes, defines, etc.
AM_CPPFLAGS = -I$(srcdir)

## Build as standalone program
bin_PROGRAMS = genrevision
genrevision_SOURCES = \
	genrevision.cpp

## Link against the shared library
genrevision_LDADD =
genrevision_LDFLAGS = -L$(libdir)

## Additional files to include when running 'make dist'
#  Include world daemon configuration
#EXTRA_DIST =

## Additional files to install
