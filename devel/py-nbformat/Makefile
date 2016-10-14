# $FreeBSD$

PORTNAME=	nbformat
PORTVERSION=	4.1.0
PORTREVISION=	1
CATEGORIES=	misc devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	gcj21@cl.cam.ac.uk
COMMENT=	Jupyter notebook format

LICENSE=	BSD3CLAUSE

RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}testpath>0:misc/py-testpath
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}traitlets>0:devel/py-traitlets
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}jupyter_core>0:devel/py-jupyter_core
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}jsonschema>2.5:devel/py-jsonschema
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}ipython_genutils>0:devel/py-ipython_genutils

USES+=		python
USE_PYTHON=	autoplist distutils

.include <bsd.port.mk>
