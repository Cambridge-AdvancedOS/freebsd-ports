# $FreeBSD$

PORTNAME=	nbconvert
PORTVERSION=	4.2.0
CATEGORIES=	misc devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	gcj21@cl.cam.ac.uk
COMMENT=	Converting Jupyter notebooks

LICENSE=	BSD3CLAUSE

RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}entrypoints>0:misc/py-entrypoints
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}Jinja2>0:devel/py-Jinja2
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}jupyter_core>0:devel/py-jupyter_core
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}mistune>0:textproc/py-mistune
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}nbformat>0:devel/py-nbformat
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}pygments>0:textproc/py-pygments
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}traitlets>0:devel/py-traitlets
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}jupyter_client>0:devel/py-jupyter_client
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}tornado>0:www/py-tornado
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}ipykernel>0:devel/py-ipykernel
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}nose>0:devel/py-nose
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}testpath>0:misc/py-testpath

USES+=		python
USE_PYTHON=	autoplist distutils

.include <bsd.port.mk>
