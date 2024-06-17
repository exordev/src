PROG=		publicaddr
NOMAN=		noman
CFLAGS+=	-W -Wall -Werror -Wextra -pedantic -ansi
LDFLAGS+=	-static
BINDIR=		${DESTDIR}/var/www/cgi-bin/

realinstall:
	mkdir -p ${BINDIR}
	cp -p ${PROG} ${BINDIR}

.include <bsd.prog.mk>
