FILES=	index.html
BINDIR=	${DESTDIR}/var/www/htdocs/josegpt

all clean cleandir tags:

realinstall:
	mkdir -p ${BINDIR}
	cp -Rp ${FILES} ${BINDIR}

.include <bsd.prog.mk>
