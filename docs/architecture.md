# Architecture

## Objective

Deploy a self-hosted email platform for learning and infrastructure development purposes.

## Physical Infrastructure

* ISP Business Connection (Static IP)
* Router
* Ubuntu Server
* Docker
* TrueNAS Backup Storage

## Logical Architecture

Internet
│
Static IP
│
Router
│
Ubuntu Server
│
Docker
└── Stalwart Mail Server

## Storage Layout

System:

* NVMe SSD

Applications:

* SSD Cache

Mail Data:

* HDD Storage

Backups:

* USB Backup Drive
