# KAMG Mail Lab

Self-hosted email infrastructure project built as part of the KAMG Solutions HomeLab.

## Project Goals

* Learn email server administration
* Deploy a self-hosted mail platform
* Configure SPF, DKIM and DMARC
* Implement backup and disaster recovery procedures
* Document infrastructure using GitHub

## Planned Technology Stack

* Ubuntu Server
* Docker
* Stalwart Mail Server
* Cloudflare DNS
* Let's Encrypt
* Uptime Kuma
* TrueNAS Storage

## Infrastructure Overview

Internet → Static IP → Router → Ubuntu Server → Docker → Stalwart Mail Server

## Project Status

* [x] GitHub repository created
* [x] Documentation structure created
* [ ] Mail server deployed
* [ ] Static IP assigned
* [ ] DNS configured
* [ ] PTR configured
* [ ] External mail delivery tested
* [ ] Backup strategy implemented
