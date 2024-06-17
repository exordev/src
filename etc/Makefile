FILES=	relayd.conf httpd.conf acme-client.conf
BINDIR=	${DESTDIR}/etc

all clean cleandir tags:

realinstall:
	mkdir -p ${BINDIR}
	cp -fp ${FILES} ${BINDIR}

.include <bsd.prog.mk>
