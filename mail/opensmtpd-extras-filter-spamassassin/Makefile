# Created by: Adam Weinberger <adamw@FreeBSD.org>
# $FreeBSD$

PKGNAMESUFFIX=		-filter-spamassassin
PORTREVISION=		2

COMMENT=		Spamassassin filter addon for OpenSMTPD

PLIST_FILES=		libexec/opensmtpd/filter-spamassassin \
			man/man8/filter-spamassassin.8.gz

CONFIGURE_ARGS+=	--with-experimental-filter-spamassassin

MASTERDIR=		${.CURDIR}/../opensmtpd-extras
SLAVE_PORT=		yes

.include "${MASTERDIR}/Makefile"
