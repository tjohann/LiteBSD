#	@(#)Makefile	8.3 (Berkeley) 3/27/94

PROG=	mount_null
SRCS=	mount_null.c getmntopts.c
MAN8=	mount_null.0

MOUNT=	${.CURDIR}/../mount
CFLAGS+= -I../../sys -I${MOUNT}
#.PATH:	${MOUNT}

.include <bsd.prog.mk>
