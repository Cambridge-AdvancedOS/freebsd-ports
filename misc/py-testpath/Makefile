# $FreeBSD$

PORTNAME=	testpath
PORTVERSION=	0.3
PORTREVISION=	1
CATEGORIES=	misc devel python
MASTER_SITES=	https://pypi.io/packages/py2.py3/t/testpath/
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}
EXTRACT_SUFX=	-py2.py3-none-any.whl

MAINTAINER=	gcj21@cl.cam.ac.uk
COMMENT=	Test utilities for code working with files and commands

LICENSE=	MIT

EXTRACT_DEPENDS=${PREFIX}/bin/pip:${PORTSDIR}/devel/py-pip

USES+=		python

do-extract:
		${MKDIR} ${WRKSRC}
		${PREFIX}/bin/pip install --no-deps --isolated \
		--ignore-installed --root=${WRKSRC}/ ${DISTDIR}/${DISTFILES}

NO_BUILD=	yes

do-install:
		${MKDIR} ${STAGEDIR}
		cd ${WRKSRC} && ${COPYTREE_SHARE} . ${STAGEDIR}

.include <bsd.port.mk>
