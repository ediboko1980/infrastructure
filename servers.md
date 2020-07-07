# GrapheneOS website

Domains:

- grapheneos.org
- www.grapheneos.org
- mta-sts.grapheneos.org
- mta-sts.mail.grapheneos.org

IPs:

- 66.70.190.239
- 2607:5300:201:3100::3a97

Ports:

- 22 ssh - no passwords
- 80 http - HTTPS redirect only
- 443 https - static

# GrapheneOS release server

Domains:

- releases.grapheneos.org
- seamlessupdate.app
- www.seamlessupdate.app
- mta-sts.seamlessupdate.app

IPs:

- 144.217.82.101
- 2607:5300:201:3100::49fe

Ports:

- 22 ssh - no passwords
- 80 http - HTTPS redirect only
- 443 https - static

# GrapheneOS time server

Domains:

- time.grapheneos.org

IPs:

- 167.114.145.173
- 2607:5300:201:3100::2ddd

Ports:

- 22 ssh - no passwords
- 443 https - no content, returns 204 response code for /

# GrapheneOS connectivity check server

Domains:

- connectivitycheck.grapheneos.org

IPs:

- 51.79.54.68
- 2607:5300:205:200:0:0:0:b44

Ports:

- 22 ssh - no passwords
- 443 https - no content, returns 204 response code for /generate\_204

# GrapheneOS mail server

Domains:

- mail.grapheneos.org

IPs:

- 51.161.8.12
- 2607:5300:205:200::40f

Ports:

- 22 ssh - no passwords
- 25 smtp - DANE TLSA
- 465 submissions - AUTH only, DANE TLSA
- 993 imaps - DANE TLSA

# Attestation website and service

Domains:

- attestation.app
- www.attestation.app
- attestation.grapheneos.org
- mta-sts.attestation.app

IPs:

- 54.39.97.128
- 2607:5300:201:3100::6dfc

Ports:

- 22 ssh - no passwords
- 80 http - HTTPS redirect only
- 443 https - static + reverse proxy to attestation service
