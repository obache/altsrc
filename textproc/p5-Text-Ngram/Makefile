# $NetBSD: Makefile,v 1.14 2021/05/24 19:54:44 wiz Exp $
#

DISTNAME=	Text-Ngram-0.15
PKGNAME=	p5-${DISTNAME}
PKGREVISION=	7
CATEGORIES=	textproc
MASTER_SITES=	${MASTER_SITE_PERL_CPAN:=Text/}

MAINTAINER=	pkgsrc-users@NetBSD.org
HOMEPAGE=	https://metacpan.org/release/Text-Ngram
COMMENT=	Ngram analysis of text
LICENSE=	${PERL5_LICENSE}

# for make test
BUILD_DEPENDS+=	p5-Unicode-CaseFold-[0-9]*:../../textproc/p5-Unicode-CaseFold

PERL5_PACKLIST=	auto/Text/Ngram/.packlist

.include "../../lang/perl5/module.mk"
.include "../../mk/bsd.pkg.mk"
