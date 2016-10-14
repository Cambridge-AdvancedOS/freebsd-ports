# $FreeBSD$

PORTNAME= 	jupyter_client
PORTVERSION=	4.4.0
PORTREVISION=	1
CATEGORIES=	misc devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	gcj21@cl.cam.ac.uk
COMMENT=	Jupyter protocol implementation and client libraries

LICENSE=	BSD3CLAUSE

RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}traitlets>0:devel/py-traitlets
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}pyzmq>=13:net/py-pyzmq
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}jupyter_core>0:devel/py-jupyter_core

USES+=		python
USE_PYTHON=	autoplist distutils

.include <bsd.port.mk>
