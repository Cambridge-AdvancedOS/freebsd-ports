# $FreeBSD$

PORTNAME= 	jupyter_core
PORTVERSION=	4.2.0
PORTREVISION=	1
CATEGORIES=	misc devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	gcj21@cl.cam.ac.uk
COMMENT=	Jupyter core package. A base package on which Jupyter \
		projects rely

LICENSE=	BSD3CLAUSE

RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}traitlets>=4.3.1:devel/py-traitlets

USES+=		python
USE_PYTHON=	autoplist distutils

.include <bsd.port.mk>
