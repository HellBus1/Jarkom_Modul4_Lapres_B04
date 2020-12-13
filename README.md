# Jarkom_Modul4_Lapres_B04

- Syubban Fakhriya  05111840000042
- Feraldy Nathanael 05111840000066

## CPT (VLSM)

**Pembagian Netmask**

**Netmask tree**

**Routing**

**Testing**

## UML (CIDR)

**Pembagian Netmask**

**Netmask tree**

**Routing**

1. SURABAYA
-------------------------------------------------------------------------
route add -net 192.168.128.0 netmask 255.255.192.0 gw 192.168.192.2
route add -net 192.168.0.0 netmask 255.255.224.0 gw 192.168.32.2
route add -net 10.151.83.44 netmask 255.255.255.252 gw 192.168.32.2

2. BATU
-------------------------------------------------------------------------
route add -net 10.151.83.44 netmask 255.255.255.252 gw 192.168.8.2
route add -net 192.168.0.0 netmask 255.255.248.0 gw 192.168.8.2
route add -net 192.168.18.0 netmask 255.255.255.240 gw 192.168.16.2

3. KEDIRI
-------------------------------------------------------------------------
route add -net 192.168.0.0 netmask 255.255.252.0 gw 192.168.4.2

4. PASURUAN
-------------------------------------------------------------------------
route add -net 192.168.128.0 netmask 255.255.240.0 gw 192.168.144.2

**Testing**