# GrapheneOS website

Domains:

- grapheneos.org
- www.grapheneos.org
- connectivitycheck.grapheneos.org
- mta-sts.grapheneos.org

IPs:

- 66.70.190.239
- 2607:5300:201:3100::3a97

Ports:

- 22 SSH - no passwords
- 80 HTTP - HTTPS redirect only
- 443 HTTPS - static

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

- 22 SSH - no passwords
- 80 HTTP - HTTPS redirect only
- 443 HTTPS - static

# GrapheneOS time server

Domains:

- time.grapheneos.org

IPs:

- 167.114.145.173
- 2607:5300:201:3100::2ddd

Ports:

- 22 SSH - no passwords
- 443 HTTPS - no content, returns 204 response code for /

# GrapheneOS mail server

Domains:

- mail.grapheneos.org

IPs:

- 51.161.8.12
- 2607:5300:205:200::40f

Ports:

- 22 SSH - no passwords
- 25 SMTP
- 465 SMTPS AUTH only
- 587 SMTP AUTH only

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

- 22 SSH - no passwords
- 80 HTTP - HTTPS redirect only
- 443 HTTPS - static + attestation service
