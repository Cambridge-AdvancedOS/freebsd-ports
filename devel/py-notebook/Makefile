# $FreeBSD$

PORTNAME= 	notebook
PORTVERSION=	4.2.3
PORTREVISION=	1
CATEGORIES=	misc devel python
MASTER_SITES=	CHEESESHOP
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	gcj21@cl.cam.ac.uk
COMMENT=	Web-based notebook environment for interactive computing

LICENSE=	BSD3CLAUSE

RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}mock>0:devel/py-mock
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}requests>0:www/py-requests
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}nose>0:devel/py-nose
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}sphinx>=1.1:textproc/py-sphinx
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}terminado>=0.3.3:net/py-terminado
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}traitlets>0:devel/py-traitlets
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}tornado>=4:www/py-tornado
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}nbformat>0:devel/py-nbformat
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}nbconvert>0:textproc/py-nbconvert
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}jupyter_core>0:devel/py-jupyter_core
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}jupyter_client>0:devel/py-jupyter_client
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}Jinja2>0:devel/py-Jinja2
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}ipython_genutils>0:devel/py-ipython_genutils
RUN_DEPENDS+=	${PYTHON_PKGNAMEPREFIX}ipykernel>0:devel/py-ipykernel

USES+=		python
USE_PYTHON=	autoplist distutils

.include <bsd.port.mk>
