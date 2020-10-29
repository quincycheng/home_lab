# My Home Lab
Just some notes for my lab.   Please move on.

## Ingredients 

### Services
 - Public DNS registration & hosting
 - Let's Encrypt
 - Redhat Account
 - VMWare Account
 - Tanzu Network Account

### Server 1 (Raspberry Pi 4)
 - CoreDNS
 - NginxProxyManager
 
### Server 2 (2 Xeon 16-core CPU, 128G RAM, 2T SSD)
 - Esx-i 7.0 update 1
 - vCenter
 - Ops Manager
 - OCP4 on vSphere
 - Tanzu Kubernetes Grid Integrated Edition on vSphere

## Procedure

### Server 1
1. Install Ubuntu OS on server 1
2. Install CoreDNS as internal DNS server 
3. (optional) Create DNS records for individual services & SSL signing
4. (optional) Install NPM on server 1

### Server 2
1. Install ESXi 7.0 update 1 or above
2. Create PTR record on DNS
3. Install vCenter from vSphere
4. Install OpenShift 4 
5. Install Tanzu Ops Manager on vSphere
6. Install BOSH Director on Ops Manager






