---
title: Alternative ZTWA on-ramps (Optional)
pcx_content_type: overview
weight: 8
layout: learning-module
---

# Alternative ZTWA on-ramps

As discussed in the previous modules, almost everything you do with the Cloudflare reverse proxy requires [adding a site](/learning-paths/zero-trust-web-access/initial-setup/add-site/) to Cloudflare. That public DNS record (or its subdomains) becomes the domain on which your users access your private applications. This method is exceptionally secure and transparent; each domain and subdomain has access to the Cloudflare web security portfolio, are inherently DDoS protected, and receive an obfuscated origin IP. For these reasons, [public hostname routing](/learning-paths/zero-trust-web-access/connect-private-applications/) is the recommended method to onboard applications for clientless user access.  However, there may be times in which a public DNS record cannot be created, or other situations that prevent administrators from using this method.

## Objectives

By the end of this module, you will be able to:

- Connect to private web applications using their private hostnames.