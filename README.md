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
| [nginx-autocert-module](https://github.com/eilandert/nginx-autocert-module) | Automatic TLS certificates built into nginx — `autocert on;` per vhost obtains, serves and renews certs (ACME) |
| [nginx-cache-turbo-module](https://github.com/eilandert/nginx-cache-turbo-module) | Edge page cache for nginx — shared-memory cache, stale-while-revalidate, probabilistic single-flight refresh |
| [nginx-error-abuse-module](https://github.com/eilandert/nginx-error-abuse-module) | nginx module that rate-limits error (404) abusers |
| [nginx-label-autoconf-module](https://github.com/eilandert/nginx-label-autoconf-module) | Traefik-style Docker-label routing as a native nginx HTTP module — a watcher reads container labels and configures vhosts |
| [nginx-strip-filter-module](https://github.com/eilandert/nginx-strip-filter-module) | Dynamic nginx response-body minifier — strips comments and redundant whitespace from HTML, CSS, JavaScript, JSON, SVG and XML while preserving syntax that affects meaning |
| [webserver-hardening](https://github.com/eilandert/webserver-hardening) | Hardening patches + config snippets for nginx, Angie and OpenSSL — the deb.myguard.nl stack |
| [vaultwarden-crs-plugin](https://github.com/eilandert/vaultwarden-crs-plugin) | OWASP CRS plugin for Vaultwarden (Bitwarden) — JSON-API-aware FP exclusions + opt-in path allowlist |
| [vimbadmin-crs-plugin](https://github.com/eilandert/vimbadmin-crs-plugin) | OWASP CRS / ModSecurity plugin for ViMbAdmin |
| [wordpress-hardening-plugin](https://github.com/eilandert/wordpress-hardening-plugin) | OWASP CRS 4.0+ (ModSecurity) plugin to harden WordPress |
| [gazor](https://github.com/eilandert/gazor) | Fast, zero-dependency Go reimplementation of the razor (Razor2) client (library + CLI) |
| [gdcc](https://github.com/eilandert/gdcc) | From-scratch, dependency-free Go DCC protocol client (library + CLI) |
| [gozer](https://github.com/eilandert/gozer) | The DCC/Razor/Pyzor rspamd backend binary — links gdcc/gazor/gyzor in-process, one authenticated HTTP endpoint, no per-message forks |
| [gyzor](https://github.com/eilandert/gyzor) | Fast, dependency-light Go reimplementation of the pyzor client (library + CLI) |
| [rspamd-dcc-razor-pyzor](https://github.com/eilandert/rspamd-dcc-razor-pyzor) | Rspamd plugin + ~6 MB distroless Go backend (gozer) scoring mail via DCC / Razor / Pyzor in-process |
| [rspamd-kam-rules](https://github.com/eilandert/rspamd-kam-rules) | Download, validate, convert and deploy KAM rules for Rspamd |
| [rspamd-olefy](https://github.com/eilandert/rspamd-olefy) | Concurrency/timeout/cache front-end wrapping Heinlein's olefy (oletools VBA-macro scanning) for busy rspamd pipelines |
| [rspamd-yarad](https://github.com/eilandert/rspamd-yarad) | YARA scanner backend for rspamd — distroless nonroot Go service, statically-linked libyara, public rulesets baked in |
| [dockerized](https://github.com/eilandert/dockerized) | Dockerized stuff |

## Dead Projects Forked & Maintaining

Abandoned upstream projects I forked and now maintain.

| Fork | Upstream | What it is |
|---|---|---|
| [zstd-nginx-module](https://github.com/eilandert/zstd-nginx-module) | [tokers/zstd-nginx-module](https://github.com/tokers/zstd-nginx-module) | ZSTD compression for nginx / Angie |
| [ViMbAdmin](https://github.com/eilandert/ViMbAdmin) | [opensolutions/ViMbAdmin](https://github.com/opensolutions/ViMbAdmin) | Modernised fork (2026) of the ViMbAdmin mail admin |
| [roundcube-elastic4mobile](https://github.com/eilandert/roundcube-elastic4mobile) | [stoyanpetrov/elastic4mobile](https://github.com/stoyanpetrov/elastic4mobile) | Mobile-optimised Elastic skin for Roundcube webmail |


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

---

## More

Curious what else is in the stack? **[Where to find us](https://deb.myguard.nl/where-to-find-us/)** lists every official repo, Docker image and download URL in one place. For a full index of everything published — packages, articles, pages — see the **[sitemap](https://deb.myguard.nl/sitemap/)**.

## Contact

Get in touch via the [contact page on deb.myguard.nl](https://deb.myguard.nl/contact/).

