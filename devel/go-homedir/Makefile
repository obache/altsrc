# $NetBSD: Makefile,v 1.33 2021/06/06 12:18:46 bsiegert Exp $

DISTNAME=	go-homedir-1.0.0
MASTER_SITES=	${MASTER_SITE_GITHUB:=mitchellh/}
PKGREVISION=	26
CATEGORIES=	devel
GITHUB_TAG=	v${PKGVERSION_NOREV}

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://github.com/mitchellh/go-homedir
COMMENT=	Go library for home directory information
LICENSE=	mit

GO_DIST_BASE=	${GITHUB_PROJECT}-${PKGVERSION_NOREV}
GO_SRCPATH=	github.com/mitchellh/go-homedir

.include "../../lang/go/go-package.mk"
.include "../../mk/bsd.pkg.mk"
