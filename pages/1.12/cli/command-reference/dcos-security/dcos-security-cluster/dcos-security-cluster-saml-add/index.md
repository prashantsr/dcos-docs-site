---
layout: layout.pug
navigationTitle:  dcos security cluster saml add
title: dcos security cluster saml add
menuWeight: 70
excerpt: Configuring a new SAML provider
enterprise: true
---
# Description

The `dcos security cluster saml add` command lets you configure a new SAML provider.

# Usage

```
dcos security cluster saml add [OPTIONS] SAML_ID
```

# Options

| Name | Description |
|-------------|-----------------|
| `-d`, `--description <text>` |  A description of the SAML provider.  (Required) |
| `-i`, `--idp-metadata <filename>` |  File containing IDP metadata in XML format. (Required) |
|  `-b`, `--sp-base-url <text>`  |  The base URL for the service provider. (Required) |
|  `-h`, `--help` | Show this message and exit.|
| `SAML_ID` | ID of SAML provider. |
