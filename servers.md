# GrapheneOS website

- OVH VPS vps2020-value-1-2-40
- 1 core
- 2 GB memory
- 40 GB storage
- 250 Mbit/s bandwidth

Domains:

- grapheneos.org
- www.grapheneos.org
- mta-sts.grapheneos.org
- mta-sts.mail.grapheneos.org

IPs:

- 192.99.43.50
- 2607:5300:201:3100::1aae

Ports:

- 22 ssh - no passwords
- 80 http - HTTPS redirect only
- 443 https - static

# GrapheneOS release server

- OVH VPS vps2020-elite-8-8-160
- 8 core
- 8 GB memory
- 160 GB storage
- 2000 Mbit/s bandwidth

Domains:

- releases.grapheneos.org
- seamlessupdate.app
- www.seamlessupdate.app
- mta-sts.seamlessupdate.app

IPs:

- 167.114.114.114
- 2607:5300:201:3100::6210

Ports:

- 22 ssh - no passwords
- 80 http - HTTPS redirect only
- 443 https - static

# GrapheneOS time server

- OVH VPS 2018 SSD 1
- 1 core
- 2 GB memory
- 20 GB storage
- 100 Mbit/s bandwidth

Domains:

- time.grapheneos.org

IPs:

- 167.114.145.173
- 2607:5300:201:3100::2ddd

Ports:

- 22 ssh - no passwords
- 443 https - no content, returns 204 response code for /

# GrapheneOS connectivity check server

- OVH VPS vps2020-starter-1-2-20
- 1 core
- 2 GB memory
- 20 GB storage
- 100 Mbit/s bandwidth

Domains:

- connectivitycheck.grapheneos.org

IPs:

- 51.79.54.68
- 2607:5300:205:200:0:0:0:b44

Ports:

- 22 ssh - no passwords
- 443 https - no content, returns 204 response code for /generate\_204

# GrapheneOS mail server

- OVH VPS 2018 SSD 1
- 1 core
- 2 GB memory
- 20 GB storage
- 100 Mbit/s bandwidth

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

- OVH VPS 2018 SSD 1
- 1 core
- 2 GB memory
- 20 GB storage
- 100 Mbit/s bandwidth

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
