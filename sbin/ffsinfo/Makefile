# $TSHeader: src/sbin/ffsinfo/Makefile,v 1.3 2000/12/05 19:45:10 tomsoft Exp $
#

GROWFS= ${.CURDIR:H}/growfs
.PATH: ${GROWFS}

PACKAGE=ufs
PROG=	ffsinfo
SRCS=	ffsinfo.c debug.c
MAN=	ffsinfo.8

WARNS?=	1
CFLAGS+=-DFS_DEBUG -I${GROWFS}
LIBADD=	ufs

.include <bsd.prog.mk>
