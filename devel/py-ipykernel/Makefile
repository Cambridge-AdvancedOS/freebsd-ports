# $FreeBSD$

PORTNAME= 	ipykernel
PORTVERSION=	4.5.0
PORTREVISION=	1
CATEGORIES=	misc devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	gcj21@cl.cam.ac.uk
COMMENT=	IPython kernel for Jupyter

LICENSE=	BSD3CLAUSE

RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}nose_warnings_filters>0:devel/py-nose_warnings_filters
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}mock>0:devel/py-mock
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}traitlets>=4.1.0:devel/py-traitlets
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}tornado>=4.0:www/py-tornado
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}jupyter_client>0:devel/py-jupyter_client
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}ipython>=4.0.0:devel/ipython

USES+=		python
USE_PYTHON=	autoplist distutils

.include <bsd.port.mk>
