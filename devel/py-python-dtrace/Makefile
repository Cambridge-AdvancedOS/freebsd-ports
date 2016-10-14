# $FreeBSD$

PORTNAME= 	python-dtrace
PORTVERSION=	0.0.9
PORTREVISION=	1
CATEGORIES=	misc devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	gcj21@cl.cam.ac.uk
COMMENT=	DTrace consumer for Python based on libdtrace

LICENSE=	MIT

BUILD_DEPENDS+=	cython:lang/cython

RUN_DEPENDS+=	${BUILD_DEPENDS}

USES+=		zip
USES+=		python
USE_PYTHON=	autoplist distutils

.include <bsd.port.mk>
