# Vitrin Chat bootstrap mirror

`manifest.json` is the Ed25519-signed endpoint document of the Vitrin Chat app (the same one its API serves at /api/v1/infra/config), republished here with a 48-hour validity so a phone that cannot reach any of the app's own names can still learn where they are.

A client trusts the signature (public key compiled into the app), never this host: a copy here can be stale, never forged. Published automatically from the app server; nothing here is edited by hand.
