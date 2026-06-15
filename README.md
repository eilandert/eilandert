# Hi, I'm eilandert 👋

I build and harden web/mail infrastructure: **nginx / Angie** (HTTP/3, big
dynamic-module set), **WordPress** performance & security, **Rspamd / Dovecot**
mail, and **OWASP CRS / ModSecurity** rule tuning. I also maintain a modernised
fork of **[ViMbAdmin](https://github.com/eilandert/ViMbAdmin)** (virtual mailbox
admin). Most of it ships through my Debian/Ubuntu APT repo at
**[deb.myguard.nl](https://deb.myguard.nl)** and as containers on
**[Docker Hub](https://hub.docker.com/u/eilandert)**.

---

## Projects Owned

Original work — authored and maintained by me.

| Project | What it is |
|---|---|
| [nginx-cache-turbo-module](https://github.com/eilandert/nginx-cache-turbo-module) | Edge page cache for nginx — shared-memory cache, stale-while-revalidate, probabilistic single-flight refresh |
| [nginx-error-abuse-module](https://github.com/eilandert/nginx-error-abuse-module) | nginx module that rate-limits error (404) abusers |
| [webserver-hardening](https://github.com/eilandert/webserver-hardening) | Hardening patches + config snippets for nginx, Angie and OpenSSL — the deb.myguard.nl stack |
| [wordpress-hardening-plugin](https://github.com/eilandert/wordpress-hardening-plugin) | OWASP CRS 4.0+ (ModSecurity) plugin to harden WordPress |
| [vaultwarden-crs-plugin](https://github.com/eilandert/vaultwarden-crs-plugin) | OWASP CRS plugin for Vaultwarden (Bitwarden) — JSON-API-aware FP exclusions + opt-in path allowlist |
| [vimbadmin-crs-plugin](https://github.com/eilandert/vimbadmin-crs-plugin) | OWASP CRS / ModSecurity plugin for ViMbAdmin |
| [rspamd-kam-rules](https://github.com/eilandert/rspamd-kam-rules) | Download, validate, convert and deploy KAM rules for Rspamd |
| [rspamd-dcc-razor-pyzor](https://github.com/eilandert/rspamd-dcc-razor-pyzor) | Rspamd plugin + s6 Debian image scoring mail via DCC / Razor / Pyzor |
| [gyzor](https://github.com/eilandert/gyzor) | Fast, dependency-light Go reimplementation of the pyzor client (library + CLI) |
| [gazor](https://github.com/eilandert/gazor) | Fast, zero-dependency Go reimplementation of the razor (Razor2) client (library + CLI) |
| [gdcc](https://github.com/eilandert/gdcc) | From-scratch, dependency-free Go DCC protocol client (library + CLI) |
| [dockerized](https://github.com/eilandert/dockerized) | Dockerized stuff |

## Dead Projects Forked & Maintaining

Abandoned upstream projects I forked and now maintain.

| Fork | Upstream | What it is |
|---|---|---|
| [zstd-nginx-module](https://github.com/eilandert/zstd-nginx-module) | [tokers/zstd-nginx-module](https://github.com/tokers/zstd-nginx-module) | ZSTD compression for nginx / Angie |
| [ViMbAdmin](https://github.com/eilandert/ViMbAdmin) | [opensolutions/ViMbAdmin](https://github.com/opensolutions/ViMbAdmin) | Modernised fork (2026) of the ViMbAdmin mail admin |


## Projects Maintaining

[**deb.myguard.nl**](https://deb.myguard.nl) — Debian/Ubuntu APT repository
where I package and keep up to date a hardened web/mail stack
([issue tracker](https://github.com/eilandert/deb.myguard.nl)):

- **[nginx](https://deb.myguard.nl/nginx-modules/)** — HTTP/3, security hardening, 100+ curated dynamic modules
- **[Angie](https://deb.myguard.nl/angie-modules-optimized-extended/)** — nextgen nginx fork, packaged with the same module set
- **[Packages](https://deb.myguard.nl/packages/)** — multiple Debian and Ubuntu packages

## Legacy, dead projects

EOL projects

| Project | What it is |
|---|---|
| [DShield.py](https://github.com/eilandert/DShield.py) | Parse Linux iptables / Snort logs into DShield format and mail them |
| [Botnet.pm](https://github.com/eilandert/Botnet.pm) | SpamAssassin module |
| [build_psol](https://github.com/eilandert/build_psol) | Build the PageSpeed Optimization Library (PSOL) |

