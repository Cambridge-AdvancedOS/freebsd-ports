# $FreeBSD$

PORTNAME=	entrypoints	
PORTVERSION=	0.2.2
POSTREVISION=	1
CATEGORIES=	misc devel python
MASTER_SITES=	https://pypi.io/packages/py2.py3/e/entrypoints/
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}
EXTRACT_SUFX=	-py2.py3-none-any.whl

MAINTAINER=	gcj21@cl.cam.ac.uk
COMMENT=	Discover and load entry points from installed packages.

LICENSE=	MIT

EXTRACT_DEPENDS=${PREFIX}/bin/pip:${PORTSDIR}/devel/py-pip

RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}configparser>=3.5:misc/py-configparser

USES+=		python

do-extract:
		${MKDIR} ${WRKSRC}
		${PREFIX}/bin/pip install --no-deps --isolated --ignore-installed --root=${WRKSRC}/ ${DISTDIR}/${DISTFILES}

NO_BUILD=	yes

do-install:
		${MKDIR} ${STAGEDIR}
		cd ${WRKSRC} && ${COPYTREE_SHARE} . ${STAGEDIR}

.include <bsd.port.mk>
