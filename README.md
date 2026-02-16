# DNS-Reconnaissance-Lab
Passive DNS reconnaissance and infrastructure footprinting lab. Implements nslookup, dig, and whois for domain mapping, reverse lookups, and registry analysis without target interaction.

# DNS Reconnaissance & Passive Information Gathering Lab
**Author:** Computer Systems Engineer Juan Pablo Vega Villamil  
**Field:** Ethical Hacking / Cyber Intelligence

---

## Lab Overview
This repository documents a professional **Passive Reconnaissance** exercise focused on the systematic gathering of intelligence via the Domain Name System (DNS). Passive reconnaissance is a critical, stealthy phase of ethical hacking where information is collected without direct interaction with the target's network or devices, thereby avoiding detection by IDS/IPS systems.

## Objectives
The primary goal is to map a target's digital footprint using public record data and standard network administrative tools:
* **Host Identification:** Utilize `nslookup` to resolve domain names and identify target IP addresses.
* **Registry Analysis:** Execute `whois` queries to extract administrative data, ownership, and registration details.
* **Comparative Tool Analysis:** Evaluate and compare the verbosity and output structure between `nslookup` and `dig` (Domain Information Groper).
* **Network Mapping:** Perform **Reverse DNS Lookups** to correlate IP addresses back to hostnames and identify infrastructure patterns.



## Technical Scenario
Before any penetration testing engagement, a "covert-first" approach is required. This lab simulates the initial phase of an audit, where publicly available domain registration data provides a wealth of information regarding an organization's internal hierarchy, mail servers (MX records), and authoritative name servers (NS records).

## Toolset
* **Nslookup:** Basic query tool for testing and troubleshooting DNS servers.
* **Dig (Domain Information Groper):** Flexible tool for interrogating DNS name servers, offering more detailed output for zone analysis.
* **Whois:** Protocol for querying databases that store the registered users or assignees of an Internet resource.

## Key Learning Outcomes
1. Ability to identify an organization's public-facing infrastructure.
2. Understanding the differences between basic and advanced DNS diagnostic tools.
3. Mastery of passive footprinting techniques to build a preliminary attack surface model.

---
**Disclaimer:** *This laboratory is for educational purposes only. All techniques were performed following ethical hacking standards using public data.*
