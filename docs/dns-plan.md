# DNS Plan

## Domain

kamg.uk

## Planned Hostnames

* mail.kamg.uk
* autodiscover.kamg.uk
* autoconfig.kamg.uk

## Required DNS Records

### A Record

mail.kamg.uk → Static Public IP

### MX Record

kamg.uk → mail.kamg.uk

### SPF Record

v=spf1 mx -all

### DKIM

To be generated after Stalwart deployment.

### DMARC

v=DMARC1; p=quarantine; rua=mailto:admin@kamg.uk
