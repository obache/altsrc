# $NetBSD: Makefile,v 1.2 2020/01/26 17:31:16 rillig Exp $

DISTNAME=	mari0-source
PKGNAME=	mari0-1.6
CATEGORIES=	games
MASTER_SITES=	http://stabyourself.net/dl.php?file=mari0-1006/
DIST_SUBDIR=	${PKGNAME_NOREV}
EXTRACT_SUFX=	.zip

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://stabyourself.net/mari0
COMMENT=	Recreation of Super Mario Bros
LICENSE=	mit # https://github.com/Stabyourself/mari0/blob/master/README.md

WRKSRC=		${WRKDIR}
USE_LANGUAGES=	# none

LOVE_GAME=	mari0
LOVE_DATA=	${PKGNAME:S/-/_/}.love
LOVE_VERSION=	0.8

.include "../../mk/love.mk"
.include "../../mk/bsd.pkg.mk"
