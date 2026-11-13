# Scope and Authorization

**Assessment:** Eselsa Technologies Attack Surface Mapping
**Date:** 2026-11-11
**Analyst:** Nwafor Arinze Jeremiah
**Assessment workstation:** Kali Linux (192.168.56.101, eth0)
**Approved subnet:** 192.168.56.0/24 (VirtualBox Host-only)
**Approved by:** Instructor Eselsa, confirmed on 2026-11-13 via WhatsApp 

## Authorized targets
- Ubuntu Server (machine25): 192.168.56.103
- Metasploitable 2: 192.168.56.102

## Excluded
- Kali's NAT adapter network (10.0.3.0/24, eth1) and everything beyond it
- All public IPs, school networks, and third-party systems

## Permitted techniques
- Host discovery
- TCP port scanning
- Service identification
- Manual service exposure review
- Passive traffic observation (Wireshark) inside the lab

## Prohibited
- Exploitation of any vulnerability
- Password / brute-force attacks
- Denial-of-service testing
- Unauthorized data access

## Answers to scope questions
1. Why must an assessment have a defined scope? 
2. What could happen if a student scans the wrong subnet? 
3. Why is authorization important even with public tools?
