# $NetBSD: Makefile,v 1.12 2021/05/24 19:53:26 wiz Exp $

DISTNAME=	Net-Domain-TLD-1.75
PKGNAME=	p5-${DISTNAME}
PKGREVISION=	5
CATEGORIES=	net perl5
MASTER_SITES=	${MASTER_SITE_PERL_CPAN:=Net/}

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://metacpan.org/release/Net-Domain-TLD
COMMENT=	Work with TLD names
LICENSE=	${PERL5_LICENSE}

PERL5_PACKLIST=	auto/Net/Domain/TLD/.packlist
#USE_LANGUAGES=	# none

.include "../../lang/perl5/module.mk"
.include "../../mk/bsd.pkg.mk"
