# 
#  Copyright 2005  Red Hat, Inc.
# 
#  Permission to use, copy, modify, distribute, and sell this software and its
#  documentation for any purpose is hereby granted without fee, provided that
#  the above copyright notice appear in all copies and that both that
#  copyright notice and this permission notice appear in supporting
#  documentation, and that the name of Red Hat not be used in
#  advertising or publicity pertaining to distribution of the software without
#  specific, written prior permission.  Red Hat makes no
#  representations about the suitability of this software for any purpose.  It
#  is provided "as is" without express or implied warranty.
# 
#  RED HAT DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE,
#  INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS, IN NO
#  EVENT SHALL RED HAT BE LIABLE FOR ANY SPECIAL, INDIRECT OR
#  CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE,
#  DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER
#  TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
#  PERFORMANCE OF THIS SOFTWARE.


bin_PROGRAMS = \
	xtrapchar \
	xtrapproto \
	xtrapin \
	xtrapout \
	xtrapstats \
	xtrapreset \
	xtrapinfo


# 
# xtrapchar
#
xtrapchar_CFLAGS = $(DEP_CFLAGS)
xtrapchar_LDADD = $(DEP_LIBS)

xtrapchar_SOURCES = \
        xtrapchar.c \
	chparse.c \
	chparse.h \
	XEKeybCtrl.c \
	XEKeybCtrl.h 

#
# xtrapin
# 
xtrapin_CFLAGS = $(DEP_CFLAGS) -D_BSD_SOURCE
xtrapin_LDADD = $(DEP_LIBS)

xtrapin_SOURCES = \
	xtrapin.c \
	XEKeybCtrl.c \
	XEKeybCtrl.h 

#
# xtrapout
#
xtrapout_CFLAGS = $(DEP_CFLAGS) -D_BSD_SOURCE
xtrapout_LDADD = $(DEP_LIBS)

xtrapout_SOURCES = \
	xtrapout.c \
	XEKeybCtrl.c \
	XEKeybCtrl.h 

#
# xtrapproto
#
xtrapproto_CFLAGS = $(DEP_CFLAGS)
xtrapproto_LDADD = $(DEP_LIBS)

xtrapproto_SOURCES = \
	xtrapproto.c

#
# xtrapreset
#
xtrapreset_CFLAGS = $(DEP_CFLAGS)
xtrapreset_LDADD = $(DEP_LIBS)

xtrapreset_SOURCES = \
	xtrapreset.c

#
# xtrapstats
#
xtrapstats_CFLAGS = $(DEP_CFLAGS)
xtrapstats_LDADD = $(DEP_LIBS)

xtrapstats_SOURCES = \
	xtrapstats.c

#
# xtrapinfo
#
xtrapinfo_CFLAGS = $(DEP_CFLAGS)
xtrapinfo_LDADD = $(DEP_LIBS)

xtrapinfo_SOURCES = \
	xtrapinfo.c \
        XEKeybCtrl.c \
	XEKeybCtrl.h 

dist_man_MANS = \
        xtrap.man

