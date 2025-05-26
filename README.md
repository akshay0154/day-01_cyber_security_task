# Task 1:  Scan Your Local Network for Open Ports
# Objective: Learn to discover open ports on devices in your local network to understand network exposure.
# Tools: Nmap

## my network 
-> adapter Mode : NAT ( i am using my collage library, it's not supported in kali linux bridge mode )
-> my ip 192.168.202.128

## Syntax 
-> nmap -sS 192.168.202.0/24 -oN result.txt

## output
Nmap scan report for 192.168.202.1
PORT     STATE SERVICE
903/tcp  open  iss-console-mgr
5357/tcp open  wsdapi
MAC Address: 00:50:56:C0:00:08 (VMware)

Nmap scan report for 192.168.202.2
PORT   STATE SERVICE
53/tcp open  domain
MAC Address: 00:50:56:E2:F0:9A (VMware)

Nmap scan report for 192.168.202.254
Not shown: 1000 filtered tcp ports (no-response)
MAC Address: 00:50:56:FC:AF:9D (VMware)

Nmap scan report for 192.168.202.128
Not shown: 1000 closed tcp ports (reset)

## uplode file
-> inculding the screenshot and the output file result.txt i already uploaded in this Github repository.
