## Module 01
To READ:
```bash
Module 01 Page 54 - Types of security policies
Module 01 Page 65 - Types of physical security
Module 01 Page 69 - What is a risk? (Formulas)
Wikipedia - GLBA (Gramm–Leach–Bliley Act) - https://en.wikipedia.org/wiki/Gramm%E2%80%93Leach%E2%80%93Bliley_Act
```

To SKIP:
```bash
Module 01 Page 155 - Cyber Law in Different countries
```

## Module 02 - Footprinting and Reconnaissance

##### Passive footprint
```bash
# Netcraft - Toolbar
https://toolbar.netcraft.com/site_report?url=protraining.lt
```


```bash
# shodan [OPTIONS] COMMAND [ARGS]...
shodan host 37.0.29.98
```


```bash
# WhatWeb - Next generation web scanner version 0.5.0.:
whatweb protraining.lt
whatweb protraining.lt -v
```

##### Footprinting tools

```bash
# dnsenum VERSION:1.2.6
# Usage: dnsenum [Options] <domain>l
dnsenum protraining.lt
```

```bash
# Old network news protocol (NNTP)
telnet news.omnitel.net 119
LIST
```

```bash
# Basic info from online tools
Netcraft
Shodan
Censys
Create alerts based on keywords and search activity
```

```bash
recon-ng
osrframework-cli
```

##### Questions
```bash
HTTP port?
DNS port?
SMTP real sender address
```
/alfarestyling/admin3472
