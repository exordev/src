FILES=	index.html err.html static
BINDIR=	${DESTDIR}/var/www/htdocs/mtaveras

all clean cleandir tags:

realinstall:
	mkdir -p ${BINDIR}
	cp -Rp ${FILES} ${BINDIR}

.include <bsd.prog.mk>
